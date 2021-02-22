# ChangePointTaylor 0.1

* Initial Release


# ChangePointTaylor 0.11

Minor bug fix release

In `change_point_analyzer_function.R` line 440 changed from  `if(!is.numeric(CI) | !dplyr::between(CI, 0.9,0.999)){` to `if(!is.numeric(min_tbl_conf) | !dplyr::between(min_tbl_conf, 0.9,0.999)){`

