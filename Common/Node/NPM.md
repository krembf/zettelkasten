##### Problem: Increase the number of file watchers
As mentioned in https://stackoverflow.com/questions/53930305/nodemon-error-system-limit-for-number-of-file-watchers-reached
```bash
sudo sysctl -w fs.inotify.max_user_watches=524288
```
-----
##### Problem: npm start unable to detect changes in node modules
###### Solution:
Try to delete node_modules/.cache folder (as mentioned in https://stackoverflow.com/questions/59401005/why-changes-made-to-a-node-module-does-not-apply-to-react-js-app):
```bash
rm -fr node_modules/.cache
```

##### Ways to start http server:
```bash
serve -s build
```
```bash
npx http-server
```