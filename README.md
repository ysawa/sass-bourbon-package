# Sass Bourbon Package

Sass and Bourbon package compatible with windows, mac os x and linux.

## About Sass

Sass has structured styles for CSS. Using this, we can generate CSS very easily even if the structures are very complex.

See http://sass-lang.com/ .

## About Bourbon

Bourbon is one of Sass plugin. The plugin includes a lot of often-used mixins and nice variables like +clearfix and $all-text-inputs. It has many advantages when we use HTML5 tags and CSS3.

See http://bourbon.io/ .

## Install

Installation is a little bit difficult for the first time.

We should install these plugins below.

1. Ruby (2.0.0 recommended)
2. Bundler
3. gem packages

### Install Ruby

#### Windows

Visit http://rubyinstaller.org/downloads/ and download Ruby 2.0.0 installer. Check if your device is x64 or not. After downloading the ruby installer, install it. If you find some checkboxes on the installation dialog, I recommend you to check the "Add Ruby executables to your PATH" checkbox.

If you are a windows user, you also need DEVELOPMENT KIT (DevKit-mingw64-32 or DevKit-mingw64-64.) Select DevKit-mingw64-64 if your device is x64. Downloading it and extract it into C:\DevKit . After extracting it, open cmd.exe in the start menu.

```
cd C:\DevKit
ruby dk.rb init

(after configuration finished, just exit) exit

ruby dk.rb install
```

This is the end of installing Ruby on your Windows.

#### Mac OS X

Visit https://rvm.io/ and copy the command for installation and paste it on your terminal. That's all.

### Install Bundler

Open your command line or terminal and execute this command

```
gem install bundler
```

It's very easy.

### Install gem packages

Download https://github.com/ysawa/sass-bourbon-package/archive/v1.1.zip , and extract it.

Next open your command line or terminal, and execute these commands.

```
cd (extracted directory path)
bundle
```

If you can execute without error, the installation has been finished.

### Guard your Sass files

Open your command line or terminal, and guard your sass files.

```
cd (extracted directory path)
bundle exec guard
```

If you are a windows user and it doesn't work well, try it.

```
cd (extracted directory path)
bundle exec guard -i
```

Then, you can edit your sass in css/sass directory. If you write right Sass codes and save the file, Guard will convert it into CSS file. It is very convenient.
