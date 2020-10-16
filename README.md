# github-actions
A demo repository for GiHub Actions

* GitHub Webhook Events `on` :
  * `push`
    * [`branches`](.github/workflows/simple-workflow.yml) - [Example runs](https://github.com/BhavyaSree/github-actions/actions?query=workflow%3ACI)
    * `branches-ignore`
    * `tags`
    * `tags-ignore`
    * [`paths`](.github/workflows/paths-event.yml) - [Example runs](https://github.com/BhavyaSree/github-actions/actions?query=workflow%3A%22Path+Events%22)
    * `paths-ignore`
  * `pull_request`
  * `schedule`
    * `cron`:  `'*/15 * * * *'`
  * `page_build`
  * `release`
    * `types`: `[published, created, edited] `
* Scheduled Events `schedule`
* External Events `Repository_dispatch`
