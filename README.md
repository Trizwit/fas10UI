<div align="center">

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-) ![Contributors](https://img.shields.io/github/contributors/Trizwit/FastnUI?color=dark-green) ![Issues](https://img.shields.io/github/issues/Trizwit/FastnUI) ![License](https://img.shields.io/github/license/Trizwit/FastnUI) [![Discord](https://img.shields.io/discord/793929082483769345)](https://discord.com/channels/793929082483769345/)

</div>

# OPEN FASTN - A platform to develop your skills through contributing to community

## About

`OPEN FASTN` will be a two week long open source contribution to FASTN Web Components Library for supporting the next generation of programmers to build their projects more easily. 

We expect this campaign will have a participation of 50+ new opensource contributors will create 250+ unique components for FASTN Component Library.

### Event timeline 
> From June 7th to June 21th 2023    

### Who can participate?
> Anyone who is interested in open source contribution can participate in OPEN FASTN.   

## Why OPEN FASTN?
- Great opportunity to contribute to the community.
- Win exciting swags.
- Get recognized for your contributions.
- Strengthen your skill by learning a powerful web development framework.

## How to participate in OPEN FASTN?
1. Join [FASTN Discord Community](https://discord.com/channels/793929082483769345/1115150105411063902)
2. Learn how to [build components](https://fastn.com/frontend/)
3. Build 5 Web Components using FASTN as per standards (To be eligible for Swag)
4. Create Pull Request to **[Trizwit/FastnUI](https://github.com/Trizwit/FastnUI)** Library Repository
5. Share your work in [OPEN FASTN Channel](https://discord.com/channels/793929082483769345/1115150105411063902) in FASTN Discord Server.


## How to contribute to Trizwit/FastnUI Repository?
### 1. Fork the repository to your Github. 📄
### 2. Open the forked repo in your code editor ( I am using VS Code ).
### 3. Create a new folder to store your components in UI-Components folder. And in it also create a component_name.ftd file.

>here my component_name is content-1 and i will be referring to it in the rest of the post.

<img src="https://github.com/Trizwit/FastnUI/blob/main/Screenshot%202023-06-02%20210017.png" width="30%" />


### 4. Copy the 1st three import statements present in **index.ftd** to content-1.ftd.
```
-- import: sarvom.github.io/component-library-tailblocks/assets
-- import: sarvom.github.io/component-library-tailblocks/lib
-- import: fastn-community.github.io/code-block as cb
```

### 5. Copy the below format, make your changes and paste it in content-1.ftd.
```
-- lib.page:

-- lib.container-wrapper:
if: { !lib.code-open }

-- content-1:
## Define your component here !!

-- end: lib.container-wrapper

-- lib.container-wrapper:
if: { lib.code-open }

-- cb.code:
lang: ftd

## Write your component code as \ (backward slash) comments in this section.

-- end: cb.code

-- end: lib.container-wrapper

-- end: lib.page

## Leave a 10 line space here : )

-- component content-1:

## write your component code here !!

-- end: content-1

```

>( ps: dont forget to remove the # comments after your done editing …! )

[Your component_name.ftd file shall look somewhat like this !](https://github.com/shaheen-senpai/FastnUI/blob/main/UI-Components/Content/content-1.ftd)

### 6. Now open the lib.ftd file and add a new button at the end in the  selector section with the url to your component_name.ftd file.
```
-- selector:

## There will be a lot of other buttons here from other contributors  

-- button: Content-1
url: UI-Components/Content/content-1

-- end: selector

```

### 7. Now save all changes and run a pre-trial on your local machine 😍

### 8. Finally commit your changes to your forked repo and sent a pull request to **Trizwit/FastnUI** Repository ⭐    

This will notify the repository maintainers of your contribution. They will review your changes, and if everything is in order, your changes will be merged into the main repository.

# Happy contributing ..!



