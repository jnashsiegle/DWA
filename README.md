# DWA - My Deployment Plan

Sites are Live 
Staging: http://198.211.110.41/
Production: http://192.34.60.127/

Requirements:

	Local Development Environment
		Git CLI
		Apache
		
	Install new server – Digital Ocean
		Git CLI
		Apache
		Server Name prodServer
		192.34.60.127

	Install second server – Digital Ocean
		Git CLI
		Apache
		Server Name stageServer
		198.211.110.41

	Backup on Github.com
		Git Push Origin

	Rough Draft Portfolio Website
		Foundation Framework Front End
		Minimum 10 Assignments/Projects displayed

	Process:
		
	Develop Website to solid foundational beginning on Localhost – MAMP

	Commit All Changes
		Commit  -a –m “relevant commit message here”
	
	Upload first to stageServer – 198.211.110.41
		Git push stageServer

	Test and Verify Site – Upon completion upload to production

	After verification / testing upload to prodServer – 192.34.60.127
		Git push prodServer

	Back up all files to github.com 
		Git push origin

	Future changes add version control
		git commit -a
		git tag -a v1.a -m 'added Readme.md Deployment Plan'
		git push stageServer -tags
		git push prodServer -tags
		git push origin - tags


		
	



