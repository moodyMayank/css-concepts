#### Separation

- The first Problem we face in using normal css is separation of the css class names and that is the hardest thing to do.
- Even if we do it , then refactoring becomes really tough and it can break some unexpected code , that will be hard to debug also.
- But in Tailwind CSS we have CSS Utility classes that are named same , so we dont need to remember them.

#### Verbosity

- In the end all the Tailwind CSS code is CSS only and also in tailwind we have to write less code for the same CSS.

#### Too Much Power

- Tailwind CSS is easy to customize unlike Bootstrap.
- BootStrap websites looks directly that bootstrap is used but that is not the case with Tailwind its that good.

#### Zombies

- Tailwind will automatically purge the unused styles and removes the dead code.

#### Drawbacks

- It is difficult to setup with 5 step process.
- Its best to use on big projects and on small projects we can use styled-components or tailwind also.

### Note : Inline fold Extension

- This extension is really useful while for inline styles , it just folds all the styles and open on clicking the elements.

#### Setup Tailwind CSS in your Project

- npm init -y

- npm install -D tailwindcss

  - Installing the Tailwind CSS Package

- npx tailwindcss init

- Setting Paths : Tailwind Config file

  - Under the Content , add the html file paths

- Add Tailwind Layers in the input.css file

  - @tailwind base;
  - @tailwind components;
  - @tailwind utilities;

- Add the npm command for build and watch , it will include input and output css files.

  - input file consists of tailwind code and custom css
  - output file consists of vanilla css , that browser will understand

- Add the output file to your html and start using the utility classes.
