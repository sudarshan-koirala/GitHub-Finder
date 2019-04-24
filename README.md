# GitHub-Finder

### Search GitHub Users and their latest repositories

- GitHub API is being used
- Change client_id & client_secret keys according to your Github profile not to restrict the user search to just 100
- the number of repositories to display can be changed
- the repositories can be shown ascending or descending order

`modification needed > github.js`

```javascript
constructor() {
    this.client_id = own key;
    this.client_secret = own key;
    this.repos_count = 5;
    this.repos_sort = 'created: asc';
  }
```

[Visit Demo Website](https://search-users-github.netlify.com/)
