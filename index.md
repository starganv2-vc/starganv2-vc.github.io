## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/starganv2-vc/starganv2-vc.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

---


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/starganv2-vc/starganv2-vc.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

---


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
## VCTK Dataset
The following audios are converted using our model trained on 20 speakers from VCTK dataset. For a fair comparision to the baseline models, all audios are downsampled to 16k Hz. We demostrate four types of conversion schemes: many-to-many, any-to-many, cross-lingual and singing conversion.

**All utterancens are partially or completely unseen during training, and the results are uncurated (NOT cherry-picked)**. 

For more audio samples, please go to our survey used for MOS evaluation [here](https://survey.alchemer.com/s3/6266556/SoundQuality2).  You may have to randomly select some answers before proceeding to the next page.

---

### Many-to-Many Conversion

The converted samples from AUTO-VC are directly taken from the survey above. Because the survey uses different sources for different models in order to prevent the rater from finding out the ground truth, the audio clips shown below are converted from sources for AUTO-VC used in the survey. 

#### Male to Male

|         | Source | Target | AUTO-VC | StarGANv2-VC |
|:-------:|:------:|:------:|:-------:|:------------:|
| **Sample1** |  p243<audio controls="controls">  <source type="audio/wav" src="https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p243xp254/source.wav"></source>    </audio> |  [p254](https://raw.githubusercontent.com/starganv2-vc/starganv2-vc.github.io/main/wav/VCTK/Seen/M2M/p243xp254/target.wav)  |         |              |
| **Sample2** |        |        |         |              |


---


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/starganv2-vc/starganv2-vc.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

---


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
