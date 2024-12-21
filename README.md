# symfony-the-fast-track

```
sudo rm -R ./vendor
sudo rm -R ./composer.lock
composer install --ignore-platform-reqs
```

```
sudo rm -R ./node_modules
sudo rm -R ./package-lock.json
sudo rm -R ./pnpm-lock.yaml
sudo rm -R ./yarn.lock
sudo rm -R ./yarn-error.log
npm cache clean --force
npm install
```


dependency-check --format ALL -s . --out owasp-dependency-report
