This folder contains the scripts to create a adp list that is color coded by the tiers you assign players. 
If you have never used the this before start wit the scraper. If you already have a tiered file, then skip to step 2.
step 1, get adp list: first use the scraper notebook to get a csv file of adp.
step 2, rank open that file in whatever software you like ot use to edit csvs. add a column named "Tier".
step 3, give them tiers: assign each player a label that represents their tier. I use the Position plus a number of dots to represent the tier so a tier to rb is "RB.."
		you can actually use any labeling you want, but the code i have for colors would have to be editted to take your tiering system.
step 4, save your csv: just save it with the same name. 
step 5, run the colorcoding script. this script will take you "PlayerRankings.csv" and create a color coded excel file that is broken up by rounds. In my case the number of rounds is twelve but you can set it to whatever you want.
step 6, update: whenever you want to update the adp, simply run the update script. Then re run the colorcoding script and boom youre done.