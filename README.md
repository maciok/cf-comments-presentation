
Documentation: https://asciidoctor.org/docs/asciidoctor-revealjs/

# Getting started
```bash
mkdir my-presentation
cd my-presentation
git init
git pull git@github.com:Glovo/glovo-presentation-template.git
# Update package.json with your presentation name
npm init -y
npm i --save asciidoctor@^2.0 @asciidoctor/reveal.js
# Now you should be able to convert the sample presentation to slides:
npx asciidoctor-revealjs presentation.adoc
```

You should be able to open presentation.html in your browser of preference

Resources from [example presentation](https://bentolor.github.io/java9to13/):
https://github.com/bentolor/java9to13/tree/master/docs
