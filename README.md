# NXP Expansion Board Hub

* Name: eb-hub-data
* Short Description: Repository that can be accessed by our trusted partners for delivery of their expansion boards files. Expansion boards will be accessible through on-line web application.
* License: CC BY-SA 4.0 (http://creativecommons.org/licenses/by-sa/4.0/)

---

## Flow
* Create your expansion board files by usig online EB-Hub data creation tool
* Place appropriatelly your files into `/data/<vendor>/` folder
* Push/commit back
* Wait for publication by NXP Authored Personel

---

### Prequesities
* For smooth process is recommended to have git latest repository cloned locally 
* Best is to functional Git env installed on your machine

---

## Publishing your changes
### Clone GitHub repository onto your hardrive
* Use following command(s) to clone the repository onto your hard drive
  ``` 
  git clone <url_to_git_repository>.git <target_directory>
  ```
### Pull latest changes from GitHub repository onto your hardrive (in case of update)
If you already clonned repository, please navigate into your git repository folder on your hard-drive and use following command(s)
  ``` 
  git pull
  ```

### Place appropriatelly your files into `/data/<vendor>/` folder

### Push your changes back into repository
* Use following command(s) to commit/push your changes back to repository
  ```
  git status
  git add *
  git commit -m "<your_changes>"
  git push
  ```

