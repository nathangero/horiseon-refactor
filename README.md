# Horiseon Refactor

## Description

- What was your motivation?
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
- What problem does it solve?
- What did you learn?

This repository is a refactored version of the Horiseon website. The goal of the refactoring was to improve the code, but keep it looking exactly the same as the original. The following changes were made:
* Improve accessibility with better HTML tags like 
* Improve readibility of the HTML and CSS file.
* Fix some website functionality.

### Description of Changes
Better HTML tags were chosen. Example:

Before:
```
<div class="header">
</div>
```

After:
```
<header>
</header>
```

Some of the CSS styling was redundant so I consolidated them under a common class, and reflected the changes on the HTML file so the style works. Example:

Before:
```
.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}
```

After:
```
.content {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.content img {
    max-height: 200px;
}

.content h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
```

You can view the refactored website [here](https://nathangero.github.io/horiseon-refactor/).


## Installation

N/A

## Usage

The site has a description of what Horiseon does, and how it can help build online repuation and social media engagement.

## Credits

N/A

## License

N/A
