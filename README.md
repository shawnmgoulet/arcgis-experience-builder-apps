# ArcGIS Experience Builder App Configurations

An Experience Builder apps config sample repo.

## What's important

1. If a `./server/public/apps` directory exists, you must rename it to something other than "apps".

2. Your apps repo must be cloned into the developer edition of Experience Builder's `./server/public` directory with the name "apps". Either: `git clone git@web-based-repo-manager:username/repo-name.git apps` or `git clone https://web-based-repo-manager/username/repo-name.git apps` should do.

3. The app names within the `apps` directory can be a string or an integer, so long as the app directory's name matches the value of the `id` property within `info.json`.
