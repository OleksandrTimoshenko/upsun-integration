# upsun-integration

1. create [trial account](https://auth.upsun.com/register)
2. create new [git repo](https://github.com/OleksandrTimoshenko/upsun-integration/)
3. Install [Upsun CLI](https://docs.upsun.com/administration/cli.html)
4. add integration to the repo from GUI or from CLI
5. clone repo, go to repo
6. connect repo to upsun `upsun project:set-remote <PROJECT_ID>`
7. init project - `git checkout -b upsun-deployment && upsun project:init`, add services during installation
8. add your code to repo - [instruction](https://docs.upsun.com/get-started/stacks/django.html)
9. [fix](https://docs.upsun.com/add-services/postgresql.html#use-in-app) env variables
10. push code to repo - `git push --set-upstream origin upsun-deployment`
11. Activate account - `upsun environment:activate`