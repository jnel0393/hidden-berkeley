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

The purpose is to give all Berkeley students a quick webpage with the most frequently used resources for convenience. I edited Morrison library's entry and added the Recreational Sports Facility (RFS) to the list. The URL for the RSF I checked is https://recwell.berkeley.edu/facilities/recreational-sports-facility-rsf/ and for Morrison https://www.lib.berkeley.edu/visit/morrison 

## Website checks

https://jnel0393.github.io/hidden-berkeley/

I added a description of hours to Morrison library because they are mostly static i.e. mon-fri 10am-5pm. Open to the public and wheelchair accessible means it is somewhere visiting family members disabled/elderly can access. 

I added the RSF because it is popular and frequently used by both undergraduate and graduate students, and I mentioned that membership or ID is required. Membership also implies that you have filled out the consent form during enrollment. 

I checked to make sure my header and description were present, my edits and addition of RSF were present, and that the links I added worked properly.

The displayed values on the webpage appear to match the values on the CSV and both URL links for Morrison and RSF work. 