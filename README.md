# rplace-v2-danielryantoby

Daniel Hill, Ryan Perez, Toby Guenthner

Position_Adjust_Parquet_Creator.ipynb:

	This takes the rplace_final.parquet and adds two new columns.
	x_rel/y_rel that are x,y positions reduced by the canvas size at the time of placement.
	Don't really need to make use of this, just for reproducability.

Complied Process.ipynb

	This goes through the entire process of reading rplace_final.parquet, getting the STD
	metrics, filtering the top 100, creating and reading those files, then making graphs
	of that and creating the mp4 animation.
