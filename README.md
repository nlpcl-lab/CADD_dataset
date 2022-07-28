# CADD_dataset
CADD: A Large-scale Comprehensive Abusiveness Detection Dataset with Multifaceted Labels from Reddit

=======================================================

* __Note__
  * 2021/09/05 New version update
  * The data is in the CSV format (encoding='latin_1').
  * Please MAKE SURE that you are fully aware of and agree to the ethical guidelines.
  * Please DO NOT modify this file directly.

## Ethical Guidelines
>1. Make no attempt to contact any user in the dataset
>2. Make no attempt to deanonymize or learn the identity of any user in the dataset
>3. Make no attempt to link users in the dataset with any external information (e.g., an account on another website)
>4. Will not share any portion of the data, including example posts or excerpts from posts, with any other party


## CADD
* __Dataset overview__

>|                                 | Values              | Description                                                                                                |
>|---------------------------------|---------------------|------------------------------------------------------------------------------------------------------------|
>| Title                           | str: Context        | Contextual information (Title + Body)                                                                      |
>| Body                            | str: Context        | Contextual information (Title + Body)                                                                      |
>| Comment                         | str: Text           | A target sentence to be classified.                                                                        |
>| L1: Type                        | {0,1,2,3}           | 0: Non-abusive, 1: Hate speech, 2: Derogatory, 3: Profanity                                                |
>| L2: Abusiveness                 | {0,1}               | 0: Non-abusive, 1: Abusive                                                                                 |
>| L3: Target                      | {0,1}               | 0: Non-targeted, 1: Targeted                                                                               |
>| L4: Demographic Characteristics | {0,1,2,3,4,5,6,7,8} | 0: None, 1:Gender, 2: Sexual orientation, 3: Race, 4: Religion 5: Disability, 6: Age, 7: Others, 8:Unclear |
>| L5: Implicitness                | {0,1}               | 0: None, 1: Implicit (Containing implicit attacks.)                                                        |
>| L6: Profanity                   | {0,1}               | 0: None, 1: Profanity (Containing any words expressing abusiveness.)                                       |


* __Data statistics__

>|     Type    |  Train | Validation |  Test |  Total |
>|:-----------:|:------:|:----------:|:-----:|:------:|
>| Hate speech |  2,515 |        388 |   772 |  3,675 |
>|  Derogatory |  1,632 |        241 |   494 |  2,367 |
>|  Profanity  |  4,595 |        631 | 1,339 |  6,565 |
>| Non-abusive |  8,412 |      1,190 | 2,297 | 11,899 |
>|     All     | 17,154 |      2,450 | 4,902 | 24,506 |



* __Annotation scheme__

  ![task2_detail](https://user-images.githubusercontent.com/40844310/132124971-68b48ac4-a69d-41a6-accf-c9a8ed7bba46.png)


## Reference

```
<a rel="reference" href="https://aclanthology.org/2021.conll-1.43.pdf">https://aclanthology.org/2021.conll-1.43.pdf</a>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

@inproceedings{song2021large,
  title={A Large-scale Comprehensive Abusiveness Detection Dataset with Multifaceted Labels from Reddit},
  author={Song, Hoyun and Ryu, Soo Hyun and Lee, Huije and Park, Jong C},
  booktitle={Proceedings of the 25th Conference on Computational Natural Language Learning},
  pages={552--561},
  year={2021}
}
```

## License

These resources are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />





