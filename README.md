# MOLE TEAM BATTLE

> Status: Active

## Purpose

This is a one-page website I created in order to host a private gaming competition as no tournament website manage the intended competition format.

## Display
The website is still currently hosted at https://www.moleteambattle.com.

The website features all its content in a single page, with an indexed menu at the top for easier navigation. As more competitions are hosted, more topics and content can be added with HTML, using the same structure. Below are a few images; if you would like to learn about the context of the competition itself, just access the website or its index page in the repo.

| ![Top of the page](perfect1.png) |
| -------------------------------- |

| ![Top of the page](perfect2.png) |
| -------------------------------- |

| ![Top of the page](perfect3.png) |
| -------------------------------- |

| ![Top of the page](perfect4.png) |
| -------------------------------- |

Although the website is managed mostly by updating its HTML according to the progression of the competitions, there are a few programmed mechanics in CSS. In order to make the Players' Ratings table look like a bulletin board to be filled with their lists so they can keep track of which players' lists are still missing during that stage in the competition, the following CSS pseudo-element ::before and pseudo-class :empty were used to automatically have the empty ordered lists of the table filled with a couple of hidden and unselectable spaces, as otherwise the table would shrink for not being entirely filled, while also removing the undesired ordered list numbers from them.

```css
table tr td ol li:empty::before {content: "\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0"}

table tr td ol li:empty {
                list-style-type: none;
            }
```

| ![Top of the page](perfect66tt.png) |
| ----------------------------------- |

| ![Top of the page](perfect77tt.png) |
| ----------------------------------- |

As for the update of the competition results in the competition board, it's basically done by updating the HTML of the following image sample, which is created with the players' names added to it manually via MS Paint.

| ![Top of the page](Primeira%20Imagem.png) |
| ----------------------------------------- |

Each time game results are established, the lines representing victories, defeats and draws are also manually added to the image, along with the heart icons being replaced with the X ones, using the same software so the updated image then replaces the older one as shown in the example below:

| ![Top of the page](Primeira%20Imagem%201.png) |
| ----------------------------------------- |

| ![Top of the page](Primeira%20Imagem%202.png) |
| ----------------------------------------- |

Once the competition is over, the board competition image with the last game results is updated with the addition of the following banner sample, in which the winner team or a draw must be declared.

| ![Top of the page](Primeira%20Imagem%203.png) |
| ----------------------------------------- |

As for the storage and sharing of the game replay files, a MEGA cloud drive was used so players can download them by accessing a hyperlink in the website.

All the media used in the website is stored in the img folder. The img-readme folder can be ignored since it's just where the images of this readme are stored.

## Development

As this was made just for a private event, I purposely did not desire this website to be easily found in the internet neither to be an actual "website", which is why stylish CSS and semantic HTML elements were intentionally avoided.

## Experience

With this project, I manage to put to practice a lot of the HTML and CSS content I studied in online technology courses, now including what I have learned about GitHub.

## Technologies
* HTML
* CSS