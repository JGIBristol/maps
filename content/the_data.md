---
draft: false
title: "The data"
weight: 1
---


## Data dictionary

The data for this project is from the Avon Longitudinal study of Parents and Children (ALSPAC, also known as Children of the 90s). For more information about the study visit http://www.bristol.ac.uk/alspac/. 

As the ALSPAC data is highly sensitive we cannot open the data to the public without ensuring the data is anonymised and non-identifiable. To achieve this an anonymised dataset will be generated using the R package SynthPop (Nowok, Raab & Dibben, 2016) on the ALSPAC data, creating the Synthetic Dataset and the Real Dataset. Participants will have access to the Synthetic Dataset but not the Real Dataset. 

The Synthetic and Real Datasets contains 15k observations of over 85 variables. A summary of the variables are shown below. A detailed description of all variables with references (where applicable) will be provided once the data is released. 

| ALSPAC variable name | Descriptive name | Variable description                                                                                                 | Administered to | Age of study child at administration | 
  |----------------------|------------------|----------------------------------------------------------------------------------------------------------------------|-----------------|--------------------------------------| 
  | b032                 | parity           | Mother's number of previous pregnancies resulting in either a live birth or a stillbirth.                            | Mother          | 18 - 20 weeks gest                   | 
| c645a                | mat_edu          | Mother’s highest educational qualification during pregnancy                                                          | Mother          | 32 weeks gestation                   | 
| c666                 | pat_edu          | Partner's highest educational qualification during pregnancy                                                         | Mother          | 32 weeks gest                        | 
  | c755                 | mat_ses          | Mother's social class during pregnancy, defined according to current or last occupation.                             | Mother          | 32 weeks gest                        | 
| c765                 | pat_ses          | Partner's social class during pregnancy, defined according to current or last occupation.                            | Mother          | 32 weeks gest                        | 
  | cce162               | tv_bed_9         | Child has TV in bedroom                                                                                              | Child           | Aged 110 months                      | 
  | ccg104               | own_mob          | Child has used their own mobile phone                                                                                | Child           | Aged 122 months                      | 
  | ccn420               | musi_13          | Child plays a musical instrument                                                                                     | Child           | Aged 157 months                      | 
  | ccq111               | mob_14_week      | Average time child spent on a school weekday talking on a mobile phone                                               | Child           | Aged 167 months                      | 
  | ccq113               | phone_14_week    | Average time child spent on a school weekday talking on an ordinary phone                                            | Child           | Aged 167 months                      | 
  | ccq131               | mob_14_wend      | Average time child spent on a weekend day talking on a mobile phone                                                  | Child           | Aged 167 months                      | 
  | ccq133               | phone_14_wend    | Average time child spent on a weekend day talking on an ordinary phone                                               | Child           | Aged 167 months                      | 
  | ccs1000              | tran_week        | Average time child spent per day in a car/bus/other transport on a typical weekday                                   | Child           | Aged 198 months                      | 
  | ccs1001              | out_sum_week     | Average time child spent per day out of doors in summer on a typical weekday                                         | Child           | Aged 198 months                      | 
  | ccs1002              | out_win_week     | Average time child spent per day out of doors in winter on a typical weekday                                         | Child           | Aged 198 months                      | 
  | ccs1003              | tv_week          | Average time child spent per day watching TV on a typical weekday                                                    | Child           | Aged 198 months                      | 
  | ccs1004              | play_week        | Average time child spent per day with other young people on a typical weekday                                        | Child           | Aged 198 months                      | 
  | ccs1005              | draw_week        | Average time child spent per day drawing/making/constructing things on a typical weekday                             | Child           | Aged 198 months                      | 
  | ccs1006              | alon_week        | Average time child spent per day doing things by yourself on a typical weekday                                       | Child           | Aged 198 months                      | 
  | ccs1007              | work_week        | Average time child spent per day doing school or college homework on a typical weekday                               | Child           | Aged 198 months                      | 
  | ccs1008              | read_week        | Average time child spent per day reading books for pleasure on a typical weekday                                     | Child           | Aged 198 months                      | 
  | ccs1009              | musi_week        | Average time child spent per day playing musical instruments on a typical weekday                                    | Child           | Aged 198 months                      | 
  | ccs1010              | comp_week        | Average time child spent per day using a computer on a typical weekday                                               | Child           | Aged 198 months                      | 
  | ccs1011              | talk_mob_week    | Average time child spent per day talking on a mobile phone on a typical weekday                                      | Child           | Aged 198 months                      | 
  | ccs1012              | text_week        | Average time child spent per day texting on a typical weekday                                                        | Child           | Aged 198 months                      | 
  | ccs1013              | talk_phon_week   | Average time child spent per day talking on an ordinary phone on a typical weekday                                   | Child           | Aged 198 months                      | 
  | ccs1020              | tran_wend        | Average time child spent per day in a car/bus/other transport on a typical weekend day                               | Child           | Aged 198 months                      | 
  | ccs1021              | out_sum_wend     | Average time child spent per day out of doors in summer on a typical weekend day                                     | Child           | Aged 198 months                      | 
  | ccs1022              | out_win_wend     | Average time child spent per day out of doors in winter on a typical weekend day                                     | Child           | Aged 198 months                      | 
  | ccs1023              | tv_wend          | Average time child spent per day watching TV on a typical weekend day                                                | Child           | Aged 198 months                      | 
  | ccs1024              | play_wend        | Average time child spent per day with other young people on a typical weekend day                                    | Child           | Aged 198 months                      | 
  | ccs1025              | draw_wend        | Average time child spent per day drawing/making/constructing things on a typical weekend day                         | Child           | Aged 198 months                      | 
  | ccs1026              | alon_wend        | Average time child spent per day doing things by yourself on a typical weekend day                                   | Child           | Aged 198 months                      | 
  | ccs1027              | work_wend        | Average time child spent per day doing school or college homework on a typical weekend day                           | Child           | Aged 198 months                      | 
  | ccs1028              | read_wend        | Average time child spent per day reading books for pleasure on a typical weekend day                                 | Child           | Aged 198 months                      | 
  | ccs1029              | musi_wend        | Average time child spent per day playing musical instruments on a typical weekend day                                | Child           | Aged 198 months                      | 
  | ccs1030              | comp_wend        | Average time child spent per day using a computer on a typical weekend day                                           | Child           | Aged 198 months                      | 
  | ccs1031              | talk_mob_wend    | Average time child spent per day talking on a mobile phone on a typical weekend day                                  | Child           | Aged 198 months                      | 
  | ccs1032              | text_wend        | Average time child spent per day texting on a typical weekend day                                                    | Child           | Aged 198 months                      | 
  | ccs1033              | talk_phon_wend   | Average time child spent per day talking on an ordinary phone on a typical weekend day                               | Child           | Aged 198 months                      | 
  | ccs2200              | child_bull       | Child has experienced bullying by another person since the age of 12                                                 | Child           | Aged 198 months                      | 
  | ccs5510              | exercise         | Frequency during the past year YP did exercise (e.g. going to the gym, brisk walking or any sports activity)         | Child           | Aged 198 months                      | 
  | f020a                | mat_anx_0m       | Mother experienced anxiety or 'nerves' since study child was born                                                    | Mother          | Aged 8 months                        | 
  | f200                 | mat_dep          | Edinburgh Post-natal Depression Scale Score                                                                          | Mother          | Aged 8 months                        | 
  | f242a                | phys_cruel       | Partner was physically cruel to mother since child was born                                                          | Mother          | Aged 8 months                        | 
  | f256a                | emot_cruel       | Partner was emotionally cruel to mother since child was born                                                         | Mother          | Aged 8 months                        | 
  | f596                 | agg_score        | Aggression score, defined by anger directed at partner, anger received from partner and arguments had with partner   | Mother          | Aged 8 months                        | 
  | f8ws112              | iq               | Weschler Intelligence Scale for Children-III - total IQ score                                                        | Clinic          | Aged around 8.5 years                | 
  | fh3010               | weight_16        | Child's weight (kg)                                                                                                  | Clinic          | Aged around 15.5 years               | 
| fh3000               |                  | Child's height (cm)                                                                                                  | Clinic          | Aged around 15.5 years               | 
  | FJCI1001             | has_dep_diag     | Child has ICD-10 diagnosis of depression, informed by their Computerised Interview Schedule - Revised (CIS-R)  score | Clinic          | Aged around 17.5 years               | 
  | FJCI350              | dep_score        | Child's depression score on CIS-R                                                                                    | Clinic          | Aged around 17.5 years               | 
| FJCI363              | dep_thoughts     | Child's number of depressive thoughts on CIS-R                                                                       | Clinic          | Aged around 17.5 years               | 
  | FJCI550              | panic_score      | Child's panic symptom score on CIS-R                                                                                 | Clinic          | Aged around 17.5 years               | 
| FJCI600              | prim_diag        | Child's primary diagnosis in accordance with ICD-10 criteria                                                         | Clinic          | Aged around 17.5 years               | 
  | FJCI601              | secd_diag        | Child's secondary diagnosis in accordance with ICD-10                                                                | Clinic          | Aged around 17.5 years               | 
| g020a                | mat_anx_8m       | Mother experienced anxiety or 'nerves' since study child was 8 months old                                            | Mother          | Aged 21 months                       | 
| h012a                | mat_anx_18m      | Mother experienced anxiety or 'nerves' since study child was 18 months old                                           | Mother          | Aged 33 months                       | 
| j11a                 | mat_anx_1        | Mother experienced anxiety or 'nerves' in the past year                                                              | Mother          | Aged 47 months                       | 
| j363                 | num_home         | Total number of people in study child's household                                                                    | Mother          | Aged 47 months                       | 
  | j374                 | pat_pres         | Biological father lives with the study child                                                                         | Mother          | Aged 47 months                       | 
  | kd381                | fam_tv_mor       | Frequency TV is on in the mornings                                                                                   | Caregiver       | Aged 18 months                       | 
  | kd382                | fam_tv_aft       | Frequency TV is on in the afternoons                                                                                 | Caregiver       | Aged 18 months                       | 
  | kd383                | fam_tv_eve       | Frequency TV is on in the evenings                                                                                   | Caregiver       | Aged 18 months                       | 
  | kl335                | comp_games       | Child has computer games                                                                                             | Caregiver       | Aged 57 months                       | 
  | kz011b               | alive_at_1       | Child alive at 1 year                                                                                                | N/A             | N/A                                  | 
  | kz021                | sex              | Sex                                                                                                                  | N/A             | N/A                                  | 
  | mz028b               | mat_age          | Grouped age of mother at delivery                                                                                    | N/A             | N/A                                  | 
  | n8050                | pat_pres_8       | Biological father lives with study child                                                                             | Caregiver       | Aged 97 months                       | 
  | kr873                | anx_band_07      | Child has any anxiety disorder                                                                                       | Caregiver       | Aged 91 months                       | 
  | kv8613               | anx_band_10      | Child has any anxiety disorder                                                                                       | Caregiver       | Aged 128 months                      | 
  | tb8614               | anx_band_13      | Child has any anxiety disorder                                                                                       | Caregiver       | Aged 166 months                      | 
  | kr859                | dep_band_07      | Child has depression                                                                                                 | Caregiver       | Aged 91 months                       | 
  | kv8603               | dep_band_10      | Child has depression                                                                                                 | Caregiver       | Aged 128 months                      | 
  | tb8603               | dep_band_13      | Child has depression                                                                                                 | Caregiver       | Aged 166 months                      | 
  | q3050                | pat_pres_10      | Biological father lives with study child                                                                             | Caregiver       | Aged 122 months                      | 
  | qlet                 | birth_order      | Order in which study child was born                                                                                  | N/A             | N/A                                  | 
  | fh6877               | anx_band_15      | Child has any anxiety disorder                                                                                       | Clinic          | Aged around 15.5 years               | 
  | fh6876               | dep_band_15      | Child has depression                                                                                                 | Clinic          | Aged around 15.5 years               | 
  | tb9523               | creat_14         | Frequency child does creative activities: art/acting/music/making things                                             | Caregiver       | Aged 166 months                      | 
  | tc0005               | q_status         | Questionnaire return status as of 10/11/09                                                                           | Caregiver       | Aged 198 months                      | 
  | tc3070               | tv_bed_16        | Study child has a TV set more or less permanently in their room                                                      | Caregiver       | Aged 166 months                      | 
  | tc3131               | comp_house       | Computer without internet access is in the study child's house but not in the study child's room                     | Caregiver       | Aged 166 months                      | 
  

## Annonymisation procedure

...Coming soon...

