## VCTK Dataset
The following audios are converted using our model trained on 20 speakers from VCTK dataset. For a fair comparision to the baseline models, all audios are downsampled to 16k Hz. We demostrate four types of conversion schemes: many-to-many, any-to-many, cross-lingual and singing conversion.

**All utterancens are partially or completely unseen during training, and the results are uncurated (NOT cherry-picked)**. 

For more audio samples, please go to our survey used for MOS evaluation [here](https://survey.alchemer.com/s3/6266556/SoundQuality2).  You may have to randomly select some answers before proceeding to the next page.

---

### Many-to-Many Conversion

The converted samples from AUTO-VC are directly taken from the survey above. Because the survey uses different sources for different models in order to prevent the rater from finding out the ground truth, the audio clips shown below are converted from sources for AUTO-VC used in the survey. 


#### Female to Female 

|              | Sample 1 (p229 → p236) | Sample 2 (p231 → p230) |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p229xp236/source.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p231xp230/source.wav"></source> </audio>  |
|    **Target**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p229xp236/target.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p231xp230/target.wav"></source> </audio> |
|    **AUTO-VC**   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p229xp236/autovc.wav"></source> </audio>    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p231xp230/autovc.wav"></source> </audio>     |
| **StarGANv2-VC** |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p229xp236/starganv2.wav"></source> </audio>     |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2F/p231xp230/starganv2.wav"></source> </audio>      |

#### Female to Male 

|              | Sample 1 (p225 → p259) | Sample 2 (p244 → p243) |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p225xp259/source.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p244xp243/source.wav"></source> </audio>  |
|    **Target**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p225xp259/target.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p244xp243/target.wav"></source> </audio> |
|    **AUTO-VC**   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p225xp259/autovc.wav"></source> </audio>    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p244xp243/autovc.wav"></source> </audio>     |
| **StarGANv2-VC** |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p225xp259/starganv2.wav"></source> </audio>     |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/F2M/p244xp243/starganv2.wav"></source> </audio>      |

#### Male to Female 

|              | Sample 1 (p226 → p233) | Sample 2 (p232 → p236) |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p226xp233/source.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p232xp236/source.wav"></source> </audio>  |
|    **Target**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p226xp233/target.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p232xp236/target.wav"></source> </audio> |
|    **AUTO-VC**   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p226xp233/autovc.wav"></source> </audio>    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p232xp236/autovc.wav"></source> </audio>     |
| **StarGANv2-VC** |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p226xp233/starganv2.wav"></source> </audio>     |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2F/p232xp236/starganv2.wav"></source> </audio>      |

#### Male to Male

|              | Sample 1 (p243 → p254) | Sample 2 (p259 → p273) |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p243xp254/source.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p259xp273/source.wav"></source> </audio>  |
|    **Target**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p243xp254/target.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p259xp273/target.wav"></source> </audio> |
|    **AUTO-VC**   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p243xp254/autovc.wav"></source> </audio>    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p259xp273/autovc.wav"></source> </audio>     |
| **StarGANv2-VC** |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p243xp254/starganv2.wav"></source> </audio>     |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p259xp273/starganv2.wav"></source> </audio>      |

---
### Any-to-Many Conversion

<center>

Our model can also convert from speakers unseen during training. One sample is shown for each case of any-to-many conversion.

#### Female to Female 

|  |p280 → p228|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/F2F/p280xp228/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/F2F/p280xp228/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/F2F/p280xp228/converted.wav"></source> </audio> |

#### Female to Male

|  |p267 → p227|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/F2M/p267xp227/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/F2M/p267xp227/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/F2M/p267xp227/converted.wav"></source> </audio> |

#### Male to Female

|  |p286 → p244|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/M2F/p286xp244/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/M2F/p286xp244/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/M2F/p286xp244/converted.wav"></source> </audio> |

#### Male to Male

|  |p287 → p273|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/M2M/p287xp273/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/M2M/p287xp273/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Unseen/M2M/p287xp273/converted.wav"></source> </audio> |

</center>

---

### Cross-lingual Conversion

<center>

We show that our model is able to convert to any language from unseen input speakers, even though the model is trained only on English data with English ASR perceptual loss. We use Korean, Japanese and Mandarin as example languages.  

#### Korean

|  |Korean male → VCTK p244|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Korean/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Korean/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Korean/p244.wav"></source> </audio> |

#### Japanese

|  |Korean male → VCTK p228|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Japanense/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Japanense/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Japanense/p228.wav"></source> </audio> |

#### Mandarin

|  |Mandarin female → VCTK p254|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Mandarin/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Mandarin/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Mandarin/p254.wav"></source> </audio> |

</center>


