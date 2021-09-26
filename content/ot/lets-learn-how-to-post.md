---
title: "តោះ! រៀន​ post"
date: 2021-02-28
update: true

tags: ["Jekyll", "tutorial", "markdown"]
categories: 
  - ពីនេះពីនោះ

author: dimorng
disqus: "enable"

draft: true

f_image: img/learn-how-to-post-f-image.jpg
---

## Embeded Card

{{< card `/linux/digraph-khmer-vowel-solution-in-ubuntu-based-distro.md` >}}

```
{{</* card `/linux/digraph-khmer-vowel-solution-in-ubuntu-based-distro.md` */>}}
```

## Link Shortcode that open target in new tab 

{{< link `Essential Guide: 21 Must-Have Apps for Ubuntu (2020 Edition)` `https://www.omgubuntu.co.uk/2016/12/21-must-have-apps-ubuntu` >}}

```
{{</* link `text` `ulr` */>}} 
```

## Emphasize quote shortcode

{{< em `The insight and experience of others is a valuable source of inspiration and motivation. And learning from successful leaders and entrepreneurs is a fantastic way to grow.` >}}

```
{{</* em `text` */>}}
```

## Hugo Buildin Shortcode
### youtube shortcode

{{< youtube Eu4zSaKOY4A >}}

```
{{</* youtube <video-id> */>}}
```

## Figure Shortcode

### Full Width Screen Figure from unsplash

{{< unsplash yBEUD8SWABc >}}

```
{{</* unsplash <photo-id> */>}}
```
### Figure with caption

{{< imgWCap how-to-install-font-in-ubuntu-based-linux-1-min.png `Font installer window` `Font Installer Window` >}}

```
{{</* imgWCap <image_file_name.extension> (`<image_alt_text>`) (`<image_caption>`) */>}}
```

### Figure without caption

{{< img how-to-install-font-in-ubuntu-based-linux-1-min.png `Font installer window` >}}

```
{{</* img <image_file_name.extension> (`<image_alt_text>`) */>}}
```

## Shortcode of Download Botton

### Download App from Offical or Trusted Website

{{< dwF `1cM67P8MbpK98WhOOnnu-QvFBUJDLopZJ` >}}

```
{{</* dwF `google_drive_id_of_file` */>}}
```

### Download pdf file

{{< pdf `1cM67P8MbpK98WhOOnnu-QvFBUJDLopZJ` >}}

```
{{</* pdf `google_drive_id_of_file` */>}}
```

* google_drive_id_of_file can be found in the link gotten from get-link command of drive.

### Download App from Offical or Trusted Website

{{< dwFW LibreOffice `https://www.libreoffice.org/download/download/` >}}

```
{{</* dwFW <App name> `<website link>` */>}}
```
### Install App from Software Manager

{{< dwFSM GIMP gimp >}}

```
{{</* dwFSM <App name> <package name> */>}}
```

### Install App from Linux Mint Software Manager

{{< dwFMS GIMP gimp >}}

```
{{</* dwFMS <App name> <package name> */>}}
```
អ្នក​អាច​រក​ឈ្មោះ​ pagckage name search `App name linux mint` ក្នុង​ web browser ។

### Andoid App for Android Device

{{< android `Flud` `https://play.google.com/store/apps/details?id=com.delphicoder.flud` >}}

```
{{</* android `<App name>` `<playstore url>` */>}}
```

### Link to GitHub Page

{{< GitHub `View Foliate GitHub Page` `https://github.com/johnfactotum/foliate/releases` >}}

```
{{</* GitHub `<text>` `link to GitHub page` */>}}
```

<figure class="full">
  <img src="https://source.unsplash.com/random/1920×1080/?nature,water" alt="Code" />
  <figcaption><span>17.3″ model running elementary OS</span></figcaption>
</figure>

Markdown ជា​ភាសា​​ប្រើ​សម្រាប់​សរសេរ​អត្ថបទ​ post ក្នុង​ Jekyll​-powered blog ។ ដោយ​សារ​ Googooraa​ ជា​ Jekyll-powered​ blog ដូច្នេះ​ ចេះ​ភាសា​ Markdown​ ជា​ការ​ចាំបាច់​ ។

បើ​តាម​ការ​អាន​ត្រួស​ ៗ​ របស់​ខ្ញុំ​ Markdown​ ជា​ភាសា​ គួរ​ឲ្យ​ចាប់​អារម្មណ៍​មួយ​ ​សាមញ្ញ​ស្រួល​រៀន​ ។

តោះ​! រៀន​​ជាមួយ​ខ្ញុំ​ ។

## ចំណងជើង​កថាខណ្ឌ​

ដើម្បី​កំណត់​ថា​ ឃ្លា​ណា​មួយ​ ជា​ចំណង​ជើង​ យើង​គ្រាន់​តែ​ដាក់​សញ្ញា​ `#` នៅ​ពី​មុខ​ឃ្លា​នោះ​ ។

ចំណងជើង​មាន​ 6 កម្រិត​ ៖

- **ចំណងជើង​កម្រិត​ 1** ឬ​ **ចំណងជើង​ធំ** កំណត់​ដោយ​មាន​សញ្ញា​ `#` 1 ពី​មុខ​ _ឧទាហរណ៍​ ៖_ `#​ ចំណងជើង​ធំ​`
- **ចំណងជើង​កម្រិត​ 2** កំណត់​ដោយ​មាន​សញ្ញា​ `#` 2 ពី​មុខ​ _ឧទាហរណ៍​ ៖_ `#​# ចំណងជើង​កម្រិត​ 2`
- **ចំណងជើង​កម្រិត​ 3** កំណត់​ដោយ​មាន​សញ្ញា​ `#` 3 ពី​មុខ​ _ឧទាហរណ៍​ ៖_ `#​## ចំណងជើង​កម្រិត​ 3`
- **ចំណងជើង​កម្រិត 4** កំណត់​ដោយ​មាន​សញ្ញា​ `#` 4 ពី​មុខ​ _ឧទាហរណ៍​ ៖_ `#​### ចំណងជើង​កម្រិត​ 4`
- **ចំណងជើង​កម្រិត​ 5** កំណត់​ដោយ​មាន​សញ្ញា​ `#` 5 ពី​មុខ​ _ឧទាហរណ៍​ ៖_ `#​#### ចំណងជើង​កម្រិត​ 5`
- **ចំណងជើង​កម្រិត​ 6** កំណត់​ដោយ​មាន​សញ្ញា​ `#` 6 ពី​មុខ​ _ឧទាហរណ៍​ ៖_ `#​##### ចំណងជើង​កម្រិត​ 6` ។

និយាយ​រួម​ ចំនួន​សញ្ញា​ `#` បញ្ជាក់​ពី​**កម្រិត​**របស់​ចំណងជើង​ ។

<aside>
 <blockquote>
  <p>ចំនួន​សញ្ញា​ <code>#</code> បញ្ជាក់​ពី​<strong>កម្រិត​</strong>របស់​ចំណងជើង​ ។</p>
 </blockquote>
</aside>

---

នេះ​ជា​ការ​បង្ហាញ​ចំណងជើង​ទាំង​ 6 កម្រិត​ខាងលើ​ ៖

# ចំណងជើង​ធំ

## ចំណងជើង​កម្រិត​ 2

### ចំណងជើង​កម្រិត​ 3

#### ចំណងជើង​កម្រិត​ 4

##### ចំណងជើង​កម្រិត​ 5

###### ចំណងជើង​កម្រិត​ 6

---

## រូបភាព

ដើម្បី​ដាក់​រូប យើង​ត្រូវ​ធ្វើ​តាម​ទម្រង់ ៖

```markdown
![alt text](URL_របស់​រូប "title text")
```

**ឧទាហរណ៍ ៖**

```markdown
![Image](https://www.webdesignerdepot.com/cdn-origin/uploads/2019/06/Medium-Mobile-Popup.png "Medium pop-ups")
```

នឹង​បង្ហាញ ៖

![Image](https://www.webdesignerdepot.com/cdn-origin/uploads/2019/06/Medium-Mobile-Popup.png "Medium pop-ups")

ក្នុង​ទាហរណ៍​ខាង​លើ ៖

- **alt text** (ពាក្យ ដែល​បង្ហាញ​ពេល​មាន​បញ្ហា​មិន​អាច​បង្ហាញ​រូបភាព​ចេញ) = Image
- **URL របស់​រូប**
- **title text** (បង្ហាញ​ពេល​រេ mouse pointer មក​ដាក់​លើ​រូប) = Mediumish logo

## Blockquotes

<aside>
  <blockquote>
    <p>Below is an excerpt of Linux++ issue 19. Be sure to read <a rel="nofollow noopener noreferrer" target="_blank" href="https://medium.com/linux-plus-plus">the full article</a>.</p>
  </blockquote>
</aside>

<a rel="nofollow noopener noreferrer" target="_blank" href="https://starlabs.systems/?rfsn=4227837.e8f025" class="button">Visit Star Labs</a>


> We are excited to team up with elementary with elementary OS now available on our laptops. With the OS being light, clean, and visually stunning, they break the boundaries for Linux going forward. The combination of elementary OS and the LabTop Mk IV creates the ultimate open source experience out of the box.
>
><span class="attribution">Sean Rhodes, Technical Project Lead at <a rel="nofollow noopener noreferrer" target="_blank" href="https://starlabs.systems/?rfsn=4227837.e8f025">Star Labs</a></span>

<a class="button" href="#">Download App via GitHub Release</a>

> We are excited to team up with elementary with elementary OS now available on our laptops. With the OS being light, clean, and visually stunning, they break the boundaries for Linux going forward. The combination of elementary OS and the LabTop Mk IV creates the ultimate open source experience out of the box.

> សុខភាព​ជា​បញ្ហា​ចម្បង​របស់​មនុស្ស​គ្រប់​រូប ! ដើម្បី​​ចូល​រួម​​ចំណែក​​លើក​​កម្ពស់​​សុខភាព​សាធារណៈនៅ​​រៀង​រាល់​​​ថ្ងៃ​​ពុធ អស់​លោក​អ្នកនាង​នឹង​បាន​ស្តាប់ សេចក្តី​អត្ថាធិប្បាយ និង​បទសម្ភាសន៍​របស់ អៀង សុខម៉ិញ ជាមួយ​​នឹង​​គ្រូពេទ្យ​​ឯកទេស ស្តី​ពី​​ប្រធានបទ​​ផ្សេងៗ​ទាក់ទង​​នឹង​​សុខភាព មានជាអាទិ៍​ការការពារការព្យាបាល។

<figure>
  <img src="https://blog.elementary.io/images/now-shipping-elementary-os/star-labs.png" alt="Laptop With Linux computer running elementary OS" />
  <figcaption>17.3″ model running elementary OS</figcaption>
</figure>

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

<div class="table">

|dss |ds s|
|---|---|
|dksk|dksk|

<div>