# Horiseon-Social-Solutions-Refactor

## Table of Contents

* [Developer Profile](#developer-profile)
* [Client Request](#client-request)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Changes](#changes)
* [Live Project Site](#live-project-site)
* [Installation and Git Repository](#installation-and-git-repository)
* [Credits](#credits)


## Developer Profile

My name is Abdulhakeem Dahir and I am an aspiring Software Developer. I have always had an interest in programming, but was too afraid to pursue a career as I felt it was too daunting of a task. Even though we are living in difficult times in 2020, I decided to take the plunge. I hope that my work will show my development as a Developer and my growth in this field. This is my first project, so here goes.

## Client Request

Our client, "Horiseon Social Solutions" requested a code refactor for their website. They wanted a more semantic, logical and consolidated code base. Most importantly though, they wanted accessibility for impaired-users. The following is the direct 'User Story' and the 'Acceptance Criteria' for the project:

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes

The follwing are all of the changes that I have made for the code refactor:

### HTML
```
- Added a new website Title
- Changed html elements to semantic elements: HEADER, NAV, MAIN, ASIDE, SECTION, and FOOTER tags.
- Added ID tags
- Linked ID tags to anchor links for in-page linking
- Changed CLASS names to more suitable variation
- Made sure code is logical and have correct hierarchy
```
### CSS
```
- Changed CSS selectors to correct elements in html
- Changed order of CSS selectors to be in line with html
- Consolidated CSS selectors
- Deleted repeating and unnecessary CSS
```

### Images
```
- Original files were over 5mb
- Used optimized and compressed files for faster load
```

## Live Project Site

https://abdulhakeemdahir.github.io/Horeseon-Social-Solutions-Refactor/

![](assets/readme-images/horiseon_refactor.png)

## Installation and Git Repository

Respository: https://github.com/abdulhakeemdahir/Horeseon-Social-Solutions-Refactor

Please follow the installation process below:
```
1. Fork the repository from the link above
2. Clone the repo to your computer via git
3. Open the project files with the text editor of your choice.
```

## Credits

A special thank you to Keenan Reed for sharing the optimized and compressed image files. 
