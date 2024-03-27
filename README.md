# devops-test

abstract: Provide lempire DEVOPS exercices
intent:

- challenge deploy skills container/vms
- challenge CI/CD understanding
- challenge tools picking

We provide you a server (devops.test.lem.ovh) with pre-installed docker. We'll provide you authentication by email.

For this test, we propose you to show your devops skills:

- Deploy jenkins or other CI/CD however you want on this server.

- Setup a CI workflow to automate:
  - a code nodejs linter for devops-test/node-app.
  - deploy suggested './nodejs-app' (or any nodejs app your choice) as a docker app. Create image, build image/ run image.

Important: We wish you expose the app to public internet, but do not expose the docker directly.

Provide your solution as a PR.

--
lempire devops team.
