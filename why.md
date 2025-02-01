---
title: Why
description: Why would one use a 40% keyboad?
published: true
date: 2025-02-01T08:17:43.986Z
tags: faq
editor: markdown
dateCreated: 2023-02-10T02:11:43.144Z
---

# Why use a 40% keyboard?

We look at three common reasons why people choose a 40% keyboard, a bit more on why layers are one of them, and make the discussion concrete with toy and complete keymap examples.

## Small, tailored, dense

People have different keyboard needs, but three common reasons for using a 40% board are:

- Small boards are easy to carry and need less desk space.
- Small is cool, cute or elegant, based on taste and needs.
- Good layers move many keys "close," making small more efficient than large.

That small things fit in more places is obvious and includes backpacks and small desks. Even with a large desk, freeing up more of it is nice. Many people also prefer mechanical keys over rubberized dome keys, and using fewer of the (bulkier) mechanical keys helps with portability.

Tailoring for the needs at hand is elegant. If you usually type just letters, why carry around physical keys for the numbers and the symbols? Expressing individuality is also a need, and smaller boards are easier and less expensive to customize than comparable larger ones. Some people like smaller boards with cool keycaps, cases and sound.

Good layering can make small boards more efficient than large unlayered ones. Layers let keys do multiple jobs based on the other keys pressed with them, just like the standard shift key does. Using 'shifted' layers for more than just capital letters means many keyboard uses can be done efficiently with just the keys right next to the fingers, including writing programs or reports. Using a large unlayered board means reaching further for keys that layers can put right under the fingers.

## Good layering

On a common laptop-sized keyboard, just under half of the keys require stretching or moving the hands followed by reorienting back to the home row; this includes distant yet common keys such as the arrow and delete keys. That reaching and reorienting is slow and can lead to hand issues.

Forty-percent keyboards reduce finger and hand stretch by moving some keys onto added layers under the fingers. Full-size keyboards already do this by using the shift key for both capital letters and many symbols. Most people don't use massive keyboards with separate keys for the capital letters and extra symbols. Instead, they use a shift-layer key. Forty-percent keyboards apply the same idea to a smaller set of base keys. They often use just the letter area plus side columns, with the keyboard usually having just four rows.

A simple 40% keymap has two new layers and two new layer access keys. Holding one layer key accesses a layer with navigation, editing, numbers, and functions; holding the other accesses a layer with symbols.

![why_layers_demo.drawio.png](/image/why_layers_demo.drawio.png)

Pressing a combination of easy-to-reach keys can be faster and easier than reaching for a distant key. Access can be by pressing the layer-access and base keys together, in sequence, or with other options. The user can customize which characters, strings or functions are on the base layer and how they access those on other layers. Common choices include a number pad, richer navigation and editing on a dedicated layer, or a leader key that outputs text snippets from short prefixes.

Layering is a tradeoff between the cognitive and finger complexity cost of accessing additional layers and the benefit of having more keys within close reach. Either because that makes the keys more accessible or because only a few keys fit in some space. Where in that tradeoff space is best depends on the situation.

Once effective layering is used, similar full-size keyboards are unneeded bulk and expense.

Many small keyboard users are programmers, a group that is often typing or editing and cares about efficiency and hand ergonomics. Sometimes a function or number row is very handy, such as for games or graphical tools with heavy function and modifier use. But for general typing, including programming, it's often better to move the distant keys to the fingers instead of the fingers to the distant keys.

In the end, small keyboards are a collection of choices and tradeoffs about people's situations, typing, and hands.

### Layer keys

If your reason for coming to a 40% keyboard often involves using many of the keys on the layers, then thumb activated layer keys in the center of the bottom row are very convenient. They allow that hand's other fingers to easily reach many of the keys on the activated layer without needing to strain or shift the hand. There are advanced layer activation techniques, with some covered in [How](/how), but the basic layer key is a simple and easy approach.

## Example keymap

As a complete example, Hillside's default keymap illustrates the more straight forward keymap techniques found among 40% keyboards.

- The letters and punctuation are on the base layer.
- Familiar side columns have shift, delete, return, etc.
- Arrow keys are on the base and/or navigation layers.
- Thumb keys give easy access to a few additional layers.
- The added layers have
    - frequent navigation and editing keys on the home row of a nav/edit layer,
    - symbols, numbers, and function keys in familiar locations.

The keymap provides familiar elements for easier initial use but also more efficient layer-based alternatives that can be grown into. The [KeymapDB](https://keymapdb.com/) has additional keymap examples for different board sizes, shapes, preferences and needs. Some additional layering techniques used with much smaller boards are described in [How](/how).

![why_keymap_hillside.drawio.png](/image/why_keymap_hillside.drawio.png)
