# ChangePointTaylor 0.1

* Initial Release


# ChangePointTaylor 0.11

Minor bug fix release

In `change_point_analyzer_function.R` line 440 changed from  `if(!is.numeric(CI) | !dplyr::between(CI, 0.9,0.999)){` to `if(!is.numeric(min_tbl_conf) | !dplyr::between(min_tbl_conf, 0.9,0.999)){`

# ChangePointTaylor 0.2

Release to fix bug that caused the argument for the number of bootstraps to only affect part of the calculation. Therefore, no matter how high you set it, the number of bootstraps stayed at the default of 1000 for part of the calculation. This issue did not affect the calculations themselves, just the number of bootstraps. 
