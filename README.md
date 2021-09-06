# CADD_dataset
CADD: A Large-scale Comprehensive Abusiveness Detection Dataset with Multifaceted Labels from Reddit

=======================================================

* __Note__
  * 2021/09/05 New version update
  * The data is in the CSV format.
  * Please DO NOT modify this file directly.

## Ethical Guidelines
>1. Make no attempt to contact any user in the dataset
>2. Make no attempt to deanonymize or learn the identity of any user in the dataset
>3. Make no attempt to link users in the dataset with any external information (e.g., an account on another website)
>4. Will not share any portion of the data, including example posts or excerpts from posts, with any other party


## CADD
* __Dataset overview__

>|                                 | Values              |                                                                                                            |
>|---------------------------------|---------------------|------------------------------------------------------------------------------------------------------------|
>| L1: Type                        | {0,1,2,3}           | 0: Non-abusive, 1: Hate speech, 2: Derogatory, 3: Profanity                                                |
>| L2: Abusiveness                 | {0,1}               | 0: Non-abusive, 1: Abusive                                                                                 |
>| L3: Target                      | {0,1}               | 0: Non-targeted, 1: Targeted                                                                               |
>| L4: Demographic Characteristics | {0,1,2,3,4,5,6,7,8} | 0: None, 1:Gender, 2: Sexual orientation, 3: Race, 4: Religion 5: Disability, 6: Age, 7: Others, 8:Unclear |
>| L5: Implicitness                | {0,1}               | 0: None, 1: Implicit (Containing implicit attacks.)                                                        |
>| L6: Profanity                   | {0,1}               | 0: None, 1: Profanity (Containing any words expressing abusiveness.)                                       |


* __Annotation scheme__

  ![task2_detail](https://user-images.githubusercontent.com/40844310/132124971-68b48ac4-a69d-41a6-accf-c9a8ed7bba46.png)



