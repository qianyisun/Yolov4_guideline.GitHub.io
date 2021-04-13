## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/qianyisun/Yolov4_guideline.GitHub.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

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

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/qianyisun/Yolov4_guideline.GitHub.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### 0. Yolov4 model introduction

### 1.Sample result

You could see the whole process by [Video Link](https://guides.github.com/features/mastering-markdown/). ??revise Link.<br>
![Image](image/dog.jpg)<br>

### 2.Basic tools or cloud introduction
#### 2.1 Github introduction
In this guideline, we are going to use GitHub which is a tool to help Internet hosting for software development and version control using Git. You could
see its details by clicking the [Link](https://en.wikipedia.org/wiki/GitHub)
##### 2.1.1 Github Basic Operation
看一下我接下来要用的。然后Github介绍下。
* git add<br>
Puts current working files into the stage.<br>
* git clone<br>
Clone an existing repository into a new directory. <br>
* git commit<br>
Commits staged changes to a local branch.<br>
* git pull<br>
Fetches remote changes on the current branch into the local clone, and merges them into the current working files.<br>
* git push<br>
Uploads changes from all local branches to the respective remote repositories.<br>

Even though we are not going to utilize other GitHub basic operation, you could learn more operations by the [Link](https://confluence.lsstcorp.org/display/LDMDG/Basic+Git+Operations)<br>

#### 2.2 Google drive and Google colab introduction
[Google drive](https://en.wikipedia.org/wiki/Google_Drive) is a great cloud file storage. Here we need to create google colab on Google drive to prepare for subsequent model establishment and object detections using Yolov4 model,etc.<br>

Google colab is an interactive environment which could allow you write and execute code.<br>

Here the website would provide the [video](https://www.youtube.com/watch?v=xoo4mTujM1U) to introduce how we could create a new google colab on Google drive.<br>


### 3. Obtaining data
If we want to train Yolov4 model to do object detection, the first thing is to obtain trained dataset. Because if we want to train any single object on model, we might need hundreds of availabe format's images. We could download the images from Google Open Images dataset V6 including about 9M images which have object bounding boxes, object segmentation masks, visual connections, and so on. In order to download these images from Google Open Images and convert them into available format image for model training, there is a [video](https://www.youtube.com/watch?v=_4A9inxGqRM) that could help us obtain available data step by step. You might need to use the [GitHub reportory](https://github.com/theAIGuysCode/OIDv4_ToolKit) if you are planning to do every step within that video.


### 4. Training data to obtain model weight
Before you do this step, you should download all file within the [link](https://drive.google.com/drive/folders/1i4j39fyD5GPjxqU-fFCVULl1qNbcuFdw?usp=sharing). After you download all files, you could open google drive and upload YOLOv4_Training_code.ipynb file into google drive. Then you are going to upload dataset and configuration files into relative address paths. Finally, you would obtain model weight after training dataset on darknet framework.<br>

Term definitions:<br>
Model weight: Model weights are all the parameters of the model which are in turn all the parameters used in the layers of the model. <br>
Darknet: Darknet is an open source neural network framework written in CUDA and C. It is fast to install and supports CPU and GPU computations.<br>

In order to repeat what I did in training data to obtain model weight, you could see the [video]()补充下Link.<br>


4.1 pull my notebook into google drive<br>
4.2 how to train ??Here is a step-by-step demonstration of opening the notebook and watching my video<br>
4.3 Specially add this to write down the introduction of file adjustment parameters<br>

### 5. Testing data on Yolov4 model

5.1 Download weights to local computer<br>
5.2 












### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
