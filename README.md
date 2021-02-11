# [Doss-Gollin Group Lab Guide](http://dossgollin-lab.github.io/lab-guide/)

This repository stores expectations and quickstart guides for the [Doss-Gollin Lab at Rice](https://dossgollin-31.github.io).
Lab and community members are encouraged to view, make comments, and propose edits.

## To view

Visit this page on the web at [`https://dossgollin-lab.github.io/lab-guide`](https://dossgollin-lab.github.io/lab-guide).

## To make comments

Use the [**Issues** tab](https://github.com/dossgollin-lab/lab-guide/issues) to share your comment.
For further instructions, see [Creating an Issue](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/creating-an-issue) in the official GitHub docs.

## To suggest edits

Start by making a comment (see above).
Then, put together a pull request to suggest edits.
If you're not familiar with the GitHub workflow for forking a repo, making changes, and submitting a pull request, check out this lab guide's [`git`/GitHub page](https://dossgollin-lab.github.io/lab-guide/toolkit/git/).

Before you submit a pull request, you may want to develop this lab guide on your own computer.

### Installing dependencies

To get this code set up (with all dependencies) on your computer you will need [`conda`](https://dossgollin-lab.github.io/lab-guide/toolkit/conda/), [`git`](https://dossgollin-lab.github.io/lab-guide/toolkit/git/), and a [GitHub](https://dossgollin-lab.github.io/lab-guide/toolkit/git/) account.
Once you have these tools 

1. Clone or fork the repo
1. Install required packages. There are several ways to do this, but the easiest is

    1. `conda env create -f environment.yml`
    1. `conda activate lab-guide`
    1. `pip install -r requirements.txt`

### Build

Once you're set up, the following steps will let you edit and serve your changes

1. Activate the conda environment: `conda activate lab-guide`
1. Open repository in your text editor and make any you want edits
1. Run `make serve` and open on your computer. You  will get a message that looks like `[I 200426 10:58:18 server:296] Serving on http://127.0.0.1:8000` in which case open `http://127.0.0.1:8000` in your web browser. You can keep making edits.

### Deploy

Once the web site looks the way you want:

1. Commit and push changes.
1. Submit a pull request if desired (see [`git`/GitHub page](https://dossgollin-lab.github.io/lab-guide/toolkit/git/) for info on how to create a PR)
1. Once your PR is approved, GitHub Actions will automatically build the website. No need to do anything!
