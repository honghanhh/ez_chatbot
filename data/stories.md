## Client form
* chao
	- utter_chao
	- utter_hoi_loai
> check_option
## Loai 1
> check_option
* loai_1
	- utter_hoi_ten
* ten
    - utter_cf_ten
    - utter_hoi_tuoi
* tuoi
	- utter_cf_tuoi
	- utter_cam_on
    
## Loai 2
> check_option
* loai_2
	- utter_hoi_ten
* ten
    - utter_cf_ten
    - utter_hoi_tuoi
* tuoi
	- utter_cf_tuoi
	- utter_cam_on

## New Story

* tam_biet
    - utter_chao
    - utter_hoi_loai
* chao
    - utter_chao
    - utter_hoi_loai
* ten{"ten":"Huyền"}
    - slot{"ten":"Huyền"}
    - utter_cf_ten
    - utter_hoi_tuoi
* tuoi{"tuoi":"10"}
    - slot{"tuoi":"10"}
    - utter_cf_tuoi
    - utter_cam_on
