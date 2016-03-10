# DWA - My Deployment Plan

Sites are Live 
*Staging:* http://198.211.110.41/
*Production:* http://192.34.60.127/

###Requirements:

1. Local Development Environment
 * Git CLI
 * Apache

2. Install New Server - Digital Ocean
  * Git CLI
  * Apache
  * Server Name prodServer
  * 192.34.60.127

3.  Install Second Server - Digital Ocean
  * Git CLI
  * Apache
  * Server Name stageServer
  * 198.211.110.41

4. Backup on [Github.com](https://github.com/jnashsiegle/DWA)

5. Rough Draft One Page Portfolio
  * Foundation Framework Front End
  * Minimum 10 Assignments/Projects displayed

###Process:

1. Develop Portfolio to solid foundational beginning on Localhost - MAMP

2.  Commit All Changes via CLI
    * Commit -a -m 'relevant commit message here'

3. Upload to stageServer - 198.211.110.41
   *Git push stageServer

4.  Test and Verify Page Functionality and Appearance

5.  Once verified upload to prodServer - 192.34.60.127
   *Git push prodServer

6.  Back up all files to github.com
   * Git push origin

7.  Future changes add version control for each section pushing first to stage until section complete then push to prodServer
   * git commit -a
   * git tag -a v1.a -m 'added Readme.md Deployment Plan'
   * git push stageServer --tags
   * git push prodServer --tags
   * git push origin --tags
 
Week 2
   * Continue website functionality and design changes throughout the week to be used in future live portfolio.  Utilize above methods of syncing prodServer and stageServer with final sync committed (for grade) by Friday 3/11/2016 11PM CST.
