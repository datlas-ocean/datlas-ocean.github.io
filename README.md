## This repo is where we develop our website. To see the rendered version go directly to  [https://www.datlas.fr](https://www.datlas.fr) 

## You can also browse some other github projects Datlas is/has been involved in :
   * MEDWEST60: [https://github.com/ocean-next/MEDWEST60](https://github.com/ocean-next/MEDWEST60)
   * SASIP: [https://github.com/sasip-climate](https://github.com/sasip-climate)
   * IMHOTEP: [https://github.com/imhotep-project](https://github.com/imhotep-project)
   * Datlas data challenges: [https://www.datlas.fr/datachallenges/](https://www.datlas.fr/datachallenges/)
   * Laurent Brodeau's sofwares (Sosie, Gonzag, Climporn, Aerobulk): [https://github.com/brodeau](https://github.com/brodeau)

## Internal note:
* __To modify the content of the website from github on-line interface:__
    * Edit the given page in the `pages` directory,
    * New images should be uploaded in the  `images` directory,
    * New blog entries (for the "news" section) should be added in the `_posts` directory,
    * Any other change in the other directories should be made with caution and with a pull request, to avoid corrupting the website template.
    * Your modifications can take a few minutes to render on the website. Be patient and don't forget to refresh your browser!
    
    
 * __If you want to hear about the details and/or if you want to develop the site locally with jekyll before pushing on github online:__
     * `bundle exec jekyll serve -w --config _config.yml` to develop locally
     * Once your satisfied with your devs and want to push to github: `bundle exec jekyll build -w --config _config.yml` to build the site, then `git add .`, `git commit -m 'YOU: my update'`, and `git push`,
     * You should know that on our o2switch web hosting I set up a redirection so that github uses directly our own domain name (www.datlas.fr) to render (CNAME entry for www.datlas.fr linked to `datlas-ocean.github.io`.
     * Be patient, your push can take several minutes before being displayed on (www.datlas.fr)[www.datlas.fr]
