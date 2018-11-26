# Calculating the Winner in Maine 2nd Congressional District

Consider [the raw votes](https://www.maine.gov/sos/cec/elec/results/results18.html) in the 2018 election for the 2nd Congressional District in Maine. Maine uses [ranked choice voting](https://en.wikipedia.org/wiki/Ranked_voting), a system which allows votes to provide a rank for each candidate on the ballot. This repo contains the raw Excel files, which allows us to replicate the state's calculations. 

## Step 1

Go from the raw xlsx files to the format in `tibble_1`. In other words, your Rmd file should begin with just the files in the repo and create a tibble with the same variables (and with rows in the same order!) as what you see in `tibble_1`.

## Step 2

Go from `tibble_1` in `tibble_2`. Don't worry about the raw files. Start with what you have in `tibble_1`, which can be read in using `read_rds()`. Produce a tibble with the same variables/ordering as `tibble_2`.

## Step 3

Start with `tibble_2`. (That is, the beginning of your Rmd file just reads in `tibble_2.rds`.) Create ggplot2 graphic which looks like the one on `base_plot.rds`. (You can see what this is by just reading it that file and printing out the object which it creates.)

## Step 4

Create an Rmd file which, when knitted, looks like `me_2.html`.
