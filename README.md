# Repository Coverage

[Full report](https://htmlpreview.github.io/?https://github.com/darrenburns/posting/blob/python-coverage-comment-action-data/htmlcov/index.html)

| Name                                                  |    Stmts |     Miss |   Cover |   Missing |
|------------------------------------------------------ | -------: | -------: | ------: | --------: |
| src/posting/\_\_init\_\_.py                           |        3 |        0 |    100% |           |
| src/posting/\_\_main\_\_.py                           |       78 |       45 |     42% |21-28, 32-41, 63-71, 79-91, 105-124, 143 |
| src/posting/app.py                                    |      567 |      103 |     82% |207, 211, 246-247, 255-262, 283, 289-304, 316, 318, 320, 336-337, 347-349, 356, 376-377, 414-415, 422-434, 454, 466, 533, 541, 558-574, 850, 903-919, 928-951, 978, 981, 997-999, 1003, 1006-1007, 1014, 1024, 1035-1050, 1059-1060, 1076-1077, 1102-1103, 1114-1121, 1130-1131 |
| src/posting/collection.py                             |      290 |       72 |     75% |23-26, 42-48, 56, 120, 211-212, 226-229, 232-243, 280-281, 328-329, 335-368, 383-384, 413-414, 433-440 |
| src/posting/commands.py                               |       46 |        4 |     91% |7, 28, 68, 70 |
| src/posting/config.py                                 |      110 |        2 |     98% |  219, 236 |
| src/posting/files.py                                  |       63 |       27 |     57% |68, 92-94, 110-146 |
| src/posting/help\_screen.py                           |       62 |        4 |     94% |   155-162 |
| src/posting/highlight\_url.py                         |        0 |        0 |    100% |           |
| src/posting/highlighters.py                           |       51 |        2 |     96% |    51, 64 |
| src/posting/importing/open\_api.py                    |      130 |      115 |     12% |36-38, 43-58, 62-87, 97-142, 148-163, 167-255, 259-266 |
| src/posting/jump\_overlay.py                          |       50 |        3 |     94% |14, 63, 69 |
| src/posting/jumper.py                                 |       33 |        1 |     97% |        54 |
| src/posting/locations.py                              |       18 |        3 |     83% |26, 31, 35 |
| src/posting/messages.py                               |        6 |        0 |    100% |           |
| src/posting/request\_headers.py                       |        8 |        0 |    100% |           |
| src/posting/save\_request.py                          |        9 |        0 |    100% |           |
| src/posting/scripts.py                                |       76 |       16 |     79% |16, 63-65, 69-70, 103-104, 131, 136, 162, 168, 197-200 |
| src/posting/suggesters.py                             |        1 |        1 |      0% |         2 |
| src/posting/themes.py                                 |      105 |        2 |     98% |   213-214 |
| src/posting/tuple\_to\_multidict.py                   |       10 |        0 |    100% |           |
| src/posting/types.py                                  |        3 |        0 |    100% |           |
| src/posting/user\_host.py                             |       11 |        2 |     82% |     14-15 |
| src/posting/variables.py                              |      102 |       21 |     79% |66-67, 103, 112, 122, 132, 137, 146, 152, 156, 162, 167-169, 178-180, 184-185, 219, 222 |
| src/posting/version.py                                |        2 |        0 |    100% |           |
| src/posting/widgets/\_\_init\_\_.py                   |        0 |        0 |    100% |           |
| src/posting/widgets/center\_middle.py                 |        3 |        0 |    100% |           |
| src/posting/widgets/collection/browser.py             |      312 |       79 |     75% |118, 128, 137, 169, 251, 259, 273-274, 283, 291, 313, 327-329, 346, 350, 355, 419-425, 431-439, 442-467, 474-481, 484-510, 523-524, 673-681 |
| src/posting/widgets/collection/new\_request\_modal.py |      122 |       12 |     90% |18, 48, 158, 178, 192-196, 199-203, 212, 217, 226-230 |
| src/posting/widgets/confirmation.py                   |       39 |       21 |     46% |51-57, 60-64, 67-72, 76, 80, 84 |
| src/posting/widgets/datatable.py                      |       91 |       31 |     66% |67, 70-73, 97-112, 115-127, 135-140 |
| src/posting/widgets/input.py                          |       61 |        2 |     97% |    33, 74 |
| src/posting/widgets/key\_value.py                     |       94 |       16 |     83% |52, 103-106, 109, 115-123, 175-177, 184 |
| src/posting/widgets/request/\_\_init\_\_.py           |        0 |        0 |    100% |           |
| src/posting/widgets/request/form\_editor.py           |       29 |        0 |    100% |           |
| src/posting/widgets/request/header\_editor.py         |       50 |        5 |     90% |   103-107 |
| src/posting/widgets/request/method\_selection.py      |       28 |        1 |     96% |        73 |
| src/posting/widgets/request/query\_editor.py          |       32 |        4 |     88% |43-44, 50-51 |
| src/posting/widgets/request/request\_auth.py          |      104 |       39 |     62% |21, 49, 117-127, 134-151, 161-164, 169-181, 192-195 |
| src/posting/widgets/request/request\_body.py          |       81 |       61 |     25% |41-45, 50-55, 57-104, 109-114, 119-130 |
| src/posting/widgets/request/request\_editor.py        |       82 |        3 |     96% |23, 141, 154 |
| src/posting/widgets/request/request\_metadata.py      |       40 |        3 |     92% |     38-40 |
| src/posting/widgets/request/request\_options.py       |       79 |       16 |     80% |123-128, 133, 140-141, 146-153 |
| src/posting/widgets/request/request\_scripts.py       |       81 |       32 |     60% |53-71, 81-110, 118, 126, 226-229 |
| src/posting/widgets/request/url\_bar.py               |      160 |       12 |     92% |75, 83, 156-157, 189-190, 196-197, 213-216, 258-259 |
| src/posting/widgets/response/cookies\_table.py        |        8 |        0 |    100% |           |
| src/posting/widgets/response/response\_area.py        |      110 |       21 |     81% |86-87, 112-113, 134-137, 143, 163, 167, 175-183, 187-190 |
| src/posting/widgets/response/response\_body.py        |       11 |        0 |    100% |           |
| src/posting/widgets/response/response\_headers.py     |        9 |        0 |    100% |           |
| src/posting/widgets/response/response\_trace.py       |       38 |        5 |     87% | 63, 75-78 |
| src/posting/widgets/response/script\_output.py        |       61 |        1 |     98% |        95 |
| src/posting/widgets/rich\_log.py                      |       26 |        0 |    100% |           |
| src/posting/widgets/select.py                         |       18 |        5 |     72% |17-20, 24, 30 |
| src/posting/widgets/tabbed\_content.py                |       12 |        6 |     50% |14-16, 19-21 |
| src/posting/widgets/text\_area.py                     |      269 |      100 |     63% |152-154, 200, 244-253, 256-279, 282-312, 412, 417, 420-425, 428, 431, 434, 437, 440, 443, 446, 449, 452-475, 478, 481, 485-499, 503-510, 514-521, 561, 573, 578-583 |
| src/posting/widgets/tree.py                           |       22 |        6 |     73% |     34-39 |
| src/posting/widgets/variable\_autocomplete.py         |       40 |        7 |     82% | 49, 74-80 |
| src/posting/widgets/variable\_input.py                |       22 |        0 |    100% |           |
| src/posting/xresources.py                             |       23 |       17 |     26% |     21-44 |
|                                             **TOTAL** | **3991** |  **928** | **77%** |           |


## Setup coverage badge

Below are examples of the badges you can use in your main branch `README` file.

### Direct image

[![Coverage badge](https://raw.githubusercontent.com/darrenburns/posting/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/darrenburns/posting/blob/python-coverage-comment-action-data/htmlcov/index.html)

This is the one to use if your repository is private or if you don't want to customize anything.

### [Shields.io](https://shields.io) Json Endpoint

[![Coverage badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/darrenburns/posting/python-coverage-comment-action-data/endpoint.json)](https://htmlpreview.github.io/?https://github.com/darrenburns/posting/blob/python-coverage-comment-action-data/htmlcov/index.html)

Using this one will allow you to [customize](https://shields.io/endpoint) the look of your badge.
It won't work with private repositories. It won't be refreshed more than once per five minutes.

### [Shields.io](https://shields.io) Dynamic Badge

[![Coverage badge](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=coverage&query=%24.message&url=https%3A%2F%2Fraw.githubusercontent.com%2Fdarrenburns%2Fposting%2Fpython-coverage-comment-action-data%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/darrenburns/posting/blob/python-coverage-comment-action-data/htmlcov/index.html)

This one will always be the same color. It won't work for private repos. I'm not even sure why we included it.

## What is that?

This branch is part of the
[python-coverage-comment-action](https://github.com/marketplace/actions/python-coverage-comment)
GitHub Action. All the files in this branch are automatically generated and may be
overwritten at any moment.