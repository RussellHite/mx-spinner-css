# mx-spinner-partial
Material Design icon font converted for use in Mendix
View icons: https://material.io/icons/

## Prerequisites
For easiest implementation of this or any other icon font it is reccomended you install the Vanilla theme when you start to style your applicaton.
https://appstore.home.mendix.com/link/app/2681/Mendix/Vanilla-Theme

## Configuration
Here are the steps to incorporate this partial into your project. 

### Step 1
Copy and paste the _spinner.scss file into the following folder your_project_folder/theme/styles/sass/lib/components
### Step 2
Open the lib.scss file under your_project_folder/theme/styles/sass and under the bottom add the following line:
```
@import "components/spinner";
```
to include the _spinner.scss file partial into the outputed css file
### Step 3
To customize spinner to your application change the font-family and content to a character that matches your application

