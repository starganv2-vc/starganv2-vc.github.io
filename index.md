## VCTK Dataset
All of the following audios are converted using **a single model trained on 20 speakers from VCTK dataset**. For a fair comparison to the baseline models, all audios are downsampled to 16k Hz. We demonstrate four types of conversion schemes: many-to-many, any-to-many, cross-lingual and singing conversion.

**All utterances are partially or completely unseen during training, and the results are uncurated (NOT cherry-picked) unless otherwise specified**.

For more audio samples, please go to our survey used for MOS evaluation [here](https://survey.alchemer.com/s3/6266556/SoundQuality2).  You may have to randomly select some answers before proceeding to the next page.

---

### Many-to-Many Conversion

The converted samples using AUTO-VC are directly taken from the survey above. We use different sources for different models in the survey to prevent the raters from finding out which sample is the ground truth, the audio clips shown below are converted from sources for AUTO-VC, which are different from those shown in the survey.


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

---

### Cross-lingual Conversion


We show that our model is able to convert to any language from unseen input speakers, even though the model is trained **only on English data with English ASR perceptual loss**. We use Korean, Japanese and Mandarin as example languages.  

#### Korean

|  |Korean male → p244|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Korean/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Korean/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Korean/p244.wav"></source> </audio> |

#### Japanese

|  |Japanese male → p228|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Japanense/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Japanense/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Japanense/p228.wav"></source> </audio> |

#### Mandarin

|  |Mandarin female → p254|
|:--:|:--:|
|**Source**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Mandarin/source.wav"></source> </audio> |
|**Target**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Mandarin/target.wav"></source> </audio> |
|**Converted**| <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Crosslingual/Mandarin/p254.wav"></source> </audio> |


---

### Singing Conversion

Lastly, we show our model can do singing conversion even though **no singing samples are seen during training**. Because both the conversion model and vocoder are trained with only speech data, there are some artifacts that resemble speech patterns. We compare our model results with Polyak et. al. Audio samples from Polyak et. al. are taken directly from their [online supplement page](https://singing-conversion.github.io/). We use the same sources from NUS-48 singing dataset and target speakers available in the selected 20 speakers.

|              | VKOW → p259 | MCUR → p233 |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p259/source.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p233/source.wav"></source> </audio>  |
|    **Target**   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p259/target.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p233/target.wav"></source> </audio>  |
|    **Polyak et. al.**   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p259/cd.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p233/cd.wav"></source> </audio>  |
| **StarGANv2-VC** |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p259/starganv2.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Singing/p233/starganv2.wav"></source> </audio>  |

---

## ESD Dataset
To demonstrate the ability of converting into stylistic speech, we train another model with 10 English speakers from the [Emotional Speech Dataset](https://github.com/HLTSingapore/Emotional-Speech-Data) (ESD). Our model can convert a neutral reading into an emotional speech. We also demostrate the ability of converting from emotional speech to emotional speech. This shows that our model can be applied to movie dubbing with proper source input. All samples are in 16k Hz. 

### Emotional to Emotional

|              | Female to Male | Male to Female |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/surprise/source.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/surprise/surprise/source.wav"></source> </audio>  |
|    **Reference**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/surprise/reference.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/surprise/surprise/reference.wav"></source> </audio> |
|    **Converted**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/surprise/converted.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/surprise/surprise/converted.wav"></source> </audio> |

### Neutral to Emotional

|              | Female to Male | Male to Female |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/plain/source.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/plain/source.wav"></source> </audio>  |
|    **Reference (neutral)**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/plain/plain/reference.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/plain/plain/reference.wav"></source> </audio> |
|    **Converted (neutral)**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/plain/plain/converted.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/plain/plain/converted.wav"></source> </audio> |
|    **Reference (emotional)**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/plain/emotional/reference.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/plain/sad/reference.wav"></source> </audio> |
|    **Converted (emotional)**    |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/F2M/plain/emotional/converted.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/EMD/M2F/plain/sad/converted.wav"></source> </audio> |

---
## JVS Dataset
[JVS dataset](https://sites.google.com/site/shinnosuketakamichi/research-topics/jvs_corpus) is a multi-speaker Japanese speech dataset that contains both regular and falsetto speech. We train a model with 130 regular speech utterances and 10 falsetto speech utterances from 10 randomly selected speakers. Our model can convert a regular speech into both regular and falsetto voices from a source of regular speech. We also show that our model can do crosslinual conversion with English source speakers from VCTK dataset, albeit trained with only Japanese corpus. All samples are in 24k Hz. 

### Female to Male (JVS 084 → JVS 006)

<table style="width: 121%;margin-left: -75px;text-align: center;">
    <thead>
        <tr>
            <th>Source</th>
            <th>Reference</th>
            <th>Converted Speech</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/F2M/source_084.wav"></source> </audio> </td>
            <td><audio controls="controls"> <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/F2M/chest_006/reference.wav"></source> </audio>(regular speech)</td>
            <td><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/F2M/chest_006/converted.wav"></source> </audio></td>
        </tr>
        <tr>
            <td rowspan=2><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/F2M/falsetto_006/reference.wav"></source> </audio>(falsetto speech)</td>
            <td><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/F2M/falsetto_006/converted.wav"></source> </audio></td>
        </tr>
    </tbody>
</table>

### Male to Female (JVS 099 → JVS 010)

<table style="width: 121%;margin-left: -75px;text-align: center;">
    <thead>
        <tr>
            <th>Source</th>
            <th>Reference</th>
            <th>Converted Speech</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/M2F/source.wav"></source> </audio> </td>
            <td><audio controls="controls"> <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/M2F/chest_010/reference.wav"></source> </audio>(regular speech)</td>
            <td><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/M2F/chest_010/converted.wav"></source> </audio></td>
        </tr>
        <tr>
            <td rowspan=2><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/M2F/falsetto_010/reference.wav"></source> </audio>(falsetto speech)</td>
            <td><audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/style/M2F/falsetto_010/converted.wav"></source> </audio></td>
        </tr>
    </tbody>
</table>

### Cross-lingual Conversion

|              | Female to Male | Male to Female |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/crosslingual/F2M/source.wav"></source> </audio>   |   <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/crosslingual/M2F/source.wav"></source> </audio> |
|    **Target**   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/crosslingual/F2M/reference.wav"></source> </audio>   |     <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/crosslingual/M2F/target.wav"></source> </audio>   |
| **Converted** |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/crosslingual/F2M/converted.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/JVS/crosslingual/M2F/converted.wav"></source>  </audio>  |


## Ablation Study

We present two samples of ablation study for conditions described in Table 2 in our paper on VCTK dataset.

|              | Sample 1 (p233 → p259) | Sample 2 (p273 → p244) |
|:------------:|:-------:|:-------:|
|    **Source**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p233_to_p259/original.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p273_to_p244/original.wav"></source> </audio>  |
|    **Target**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p233_to_p259/reference.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p273_to_p244/reference.wav"></source> </audio>  |
|    **Full StarGANv2-VC**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p233_to_p259/full.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p273_to_p244/full.wav"></source> </audio>  |
|    **No F0 Consistency Loss**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p233_to_p259/no_F0.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p273_to_p244/no_F0.wav"></source> </audio>  |
|    **No Speech Consistency Loss**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p233_to_p259/no_ASR.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p273_to_p244/no_asr.wav"></source> </audio>  |
|    **No Norm Consistency Loss**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p233_to_p259/no_norm.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p273_to_p244/no_norm.wav"></source> </audio>  |
|    **No Adversarial Source Classifier Loss**    |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p233_to_p259/no_advcls.wav"></source> </audio>   |    <audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/Ablation/p273_to_p244/no_advcls.wav"></source> </audio>  |
