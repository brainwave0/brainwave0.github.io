---
layout: post
title:  "How to Use grabcraft2txt"
---

A while back I made something called [grabcraft2txt](https://github.com/brainwave0/grabcraft2txt) which can be used to generate Minecraft build instructions in step-by-step text format. When following instructions of this format, there are some mistakes you can make that might detail your progress and slow you down. To make things easier, I will explain some solutions I have learned.

# Use Scaffolding

Scaffolding is a great block to use for filling empty space. They're easy to place, and they make it easy to move around your build without much risk of falling.

## Obtaining

For this you might want cheats enabled, depending on the size of your project. Unless you have a lot of string available, crafting scaffolding can get expensive.

### Command

To obtain scaffolding via the command line, use the following example:

```
give @s minecraft:scaffolding 256
```

This should send four stacks of scaffolding straight to your inventory. In case you don't already know, the forward slash (`/`) opens the command prompt. You can use the Tab key to complete suggestions, or just copy and paste the command.

I recommend having no more than four stacks so as to not to take up too much space in your inventory.

### Crafting

If you'd rather craft your scaffolding, you'll need some string and bamboo. You can get string from spiders and spider webs, and bamboo from bamboo forests. Bamboo is easy to grow in large quantities.

## Usage

To use scaffolding in your project, simply place one block where you need it, then place the rest by doing the place action on the top of the scaffolding while facing the direction you want it to go.

In case you need to place a long row of scaffolding, make a stack with the exact number you'll need. To do this, take advantage of the feature where you can divide a stack in two as in the following example.

If you have a stack of 64, and you need 18, do the following:

1. Right-click the stack of 64 to get 32.
2. Right-click that to get 16. You should now have stacks of 32, 16, and 16.
3. Right-click a stack of 16 to get 8.
4. Right-click that to get 4.
5. Repeat to get 2.
6. Drag the 2 onto a 16 to get 18.

While building you may want to see the progress you've made and take down all the scaffolding. For big projects I don't recommend doing this often as it can really slow you down.

# Use Signs

Eventually you will lose track of where you left off, or worse, follow the directions from the wrong place. In order to find your place again you should place signs for each row and layer. Each sign would have the number for the corresponding row or layer. If you're building really tall, you may want to build a horizontal row of dirt near the layer where you're working and place signs on that so that you don't have to go down too far to read them.
