# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is designed for incoming students, new visitors, and campus members to discover essential resources and lesser-known study spots around UC Berkeley. In addition to the original curated locations, this updated version includes the Free Speech Movement (FSM) Café located in Moffitt Library, which serves as a popular student space for studying and relaxing. The added resource information and official links were verified through the official UC Berkeley Library webpage (UC Berkeley Library - Moffitt Library).

## Website checks

The live guide is published at https://claudiaxu89.github.io/hidden_berkeley/.
In this update, I improved the access note and verified source URL for Morrison Library (HB03), and added the FSM Café (HB09) as a new campus resource. The published website is confirmed to show all nine entries properly with the updated heading and introduction. 
All displayed categories, areas, and access notes accurately match the data in docs/_data/locations.csv, and all official links including the updated and new URLs—successfully open their intended pages.
