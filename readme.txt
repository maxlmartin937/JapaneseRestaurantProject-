2/20/23 
	Added dropdown nav button, previously was 4 hyper links in header
	Adjusted background contrast 
	edited logo for contrast in photo editor 
	Included meta info, added Google Fonts as well as Bootstrap 5 CSS/JS 
	Added more responsive rules for mobile/tablet users
2/21/23 
	Restructured header html to incorporate nav bar w/ dropdown feature 
	
	Changed dropdown for links to have vertical alignment 
	
	Included more responsive rules for logo image, prev was clipping into 		body at lower resolutions
	
	Used Bootstrap 5 to add more responsive navigation bar 
	-Currently having problem opening dropdown @ medium screenwidths, 
		plan on fixing that and incorporating on other pages
2/23/23 
	Issues with responsive nav bar were resolved.  
	Fixed the issue by reformatting the nav bar and header completely. Previously, the nav bar would drop down behind the header background image. 
	The fix: 
		Built new navbar out of vanilla CSS without framework (removed BS5 elements from project) 
		Added index.js for a responsive dropdown button script
	Format Issues (resolved) 
		Rebuilt site from boilerplate 
		Simplified html, dried up significantly when removing BS5 
	Styles 
		Copied usable elements from previous iteration, added styles for new class elements used by the new nav bar and dropdown 
		Dried up unused code from prior version 
	Notes: This iteration was basically built from the bottom up with some of the sections grabbed from the previous version. Ultimately I could not find the solution for the responsive nav bar and decided to build from scratch around this design element. This has definitely been a lesson in having a plan for the features I'll be including in future projects. Some planning ahead and forethought into it woulve certainly saved me a headache. Yesterday, the 22nd, I had spent the day looking into the issue without any success, so I made a plan to implement a new system today. All in all I'm pretty happy with the current result. 

2/24/23 
	Added googlemaps extension to "directions" page 
	Added contact form ("Contact" page) 
	Started "About Us" Page 
		Had issues with divs overflowing onto each other w/ lower screen widths  
		Changed img and <p> branches into 2 seperate divs 
		decreased margins for better responsive design, still have some word wrapping which I'll adress in the future. Only really happens when changing 		 between widths and outside of common device screen widths. 

	Definitely a lot for today! Been suffering a cold for the last day and 	it's kicking my butt lol
2/24 Note: Realized logo and images werent showing due to github pages being case sensitive. Used 'git config core.ignorecase false' to update the folders name and confirmed all .img files had the correct case. 		







I unfortunately lost the local files for the original repo, so I decided to created a new one. 

The original was originally made on 2/12/23 with two commits 

<<<<<<< HEAD
Definitely a learning experience about moving/copying/deleting my .git files...
=======
Definitely a learning experience about moving/copying/deleting my .git files...
	
>>>>>>> 8decd5c71b8657ad202e258bd06e8b9321ae5da0
