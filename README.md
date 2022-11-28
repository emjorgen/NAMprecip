# NAMprecip

Author:
  Ellen May Jorgensen

Data download:
  From CESM isotope enabled model runs, ingetrated vapor transport and geopotential height
  Under 6 senarios: Uniform warming SST X1, uniform warming SST X2, marine heat wave 1, marine heatwave 2, marine heatwave 3, marine heatwave 4
  Converts netcdf files to Pandas dataframes
  Note: GPH files are too complicated to run on CoLab RAM; files must be split

NAM_Z3_IVT:
  Altered data download and preprocessing to suit CCA
  Z3 = geopotential height; IVT = ingegrated vapor transport
  limited lat, lon for both; working on limiting lev for Z3 (limit to one atmospheric level)
  calculated variance for each of 6 senarios for both variables (12 total)
  applied CCA to 6 relationships based on 6 senarios of warming (as seen above in data download description)
  
