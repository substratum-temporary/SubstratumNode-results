# Results From Builds of SubstratumNode

If you're a contributor to SubstratumNode, then when you submit a pull request to GitHub, an automatic build will be
built in our public CI. If it proceeds to the test stage, various artifacts will be collected from the build, packaged into
a gzipped TAR file, and listed here under the branch that is being reviewed. (If the build fails in the first or second stage, no tests
will have run, and all the results from the build will be available in the Azure Pipelines CI console, so no results will
appear here.)

If your build was successful, you'll find a distributable Electron application (as well as command-line binaries) in your
`generated.tar.gz` file. If it was unsuccessful, you won't find the Electron application, but you'll find results generated 
from running tests that may help you understand why the build failed. These results are the same as those you'd find on
your own machine in the ...`/generated` directories after running the tests.

We only keep track of your most recent results; they will overwrite any former results you might have had listed.

We'll keep hosting a particular set of results for _awhile._  Basically, if the results of your build don't cause a 
problem for the community--perhaps by being unmanageably large, or by having a name that looks like an injection attack,
or by anything else that annoys us--we'll keep it around until you generate another set.

### Results:

[comment]: # (Results Marker)
* Fri May  7 18:54:38 UTC 2021 - refs/heads/master (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/heads/master/generated-mac.tar.gz?raw=true)
* Thu Jan 28 20:22:03 UTC 2021 - dependabot/npm_and_yarn/node-ui/render-process/electron-9.4.0 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/electron-9.4.0/generated-mac.tar.gz?raw=true)
* Fri Dec 11 22:07:01 UTC 2020 - dependabot/npm_and_yarn/node-ui/main-process/ini-1.3.8 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/main-process/ini-1.3.8/generated-mac.tar.gz?raw=true)
* Fri Sep 11 14:45:03 UTC 2020 - dependabot/npm_and_yarn/node-ui/main-process/yargs-parser-13.1.2 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/main-process/yargs-parser-13.1.2/generated-mac.tar.gz?raw=true)
* Thu Sep 10 14:57:20 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/http-proxy-1.18.1 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/http-proxy-1.18.1/generated-mac.tar.gz?raw=true)
* Mon Sep  7 12:11:03 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/handlebars-4.7.6 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/handlebars-4.7.6/generated-mac.tar.gz?raw=true)
* Sun Sep  6 12:39:31 UTC 2020 - dependabot/npm_and_yarn/node-ui/main-process/tree-kill-1.2.2 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/main-process/tree-kill-1.2.2/generated-mac.tar.gz?raw=true)
* Wed Jul  8 00:14:50 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/npm-registry-fetch-4.0.5 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/npm-registry-fetch-4.0.5/generated-mac.tar.gz?raw=true)
* Tue Jul  7 08:41:22 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/electron-7.2.4 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/electron-7.2.4/generated-mac.tar.gz?raw=true)
* Tue Jul  7 08:37:24 UTC 2020 - dependabot/npm_and_yarn/node-ui/main-process/electron-7.2.4 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/main-process/electron-7.2.4/generated-mac.tar.gz?raw=true)
* Sun Jun  7 08:37:09 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/websocket-extensions-0.1.4 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/websocket-extensions-0.1.4/generated-mac.tar.gz?raw=true)
* Thu Apr 16 22:06:06 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/https-proxy-agent-2.2.4 (linux) - Failed: [generated-linux.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/https-proxy-agent-2.2.4/generated-linux.tar.gz?raw=true)
* Thu Apr 16 22:03:19 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/https-proxy-agent-2.2.4 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/https-proxy-agent-2.2.4/generated-mac.tar.gz?raw=true)
* Sun Apr  5 07:03:19 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/acorn-6.4.1 (linux) - Failed: [generated-linux.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/acorn-6.4.1/generated-linux.tar.gz?raw=true)
* Sun Apr  5 06:57:54 UTC 2020 - dependabot/npm_and_yarn/node-ui/render-process/acorn-6.4.1 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/acorn-6.4.1/generated-mac.tar.gz?raw=true)
* Sat Mar 14 07:07:45 UTC 2020 - dependabot/npm_and_yarn/node-ui/main-process/acorn-7.1.1 (linux) - Failed: [generated-linux.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/main-process/acorn-7.1.1/generated-linux.tar.gz?raw=true)
* Sat Mar 14 06:57:39 UTC 2020 - dependabot/npm_and_yarn/node-ui/main-process/acorn-7.1.1 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/main-process/acorn-7.1.1/generated-mac.tar.gz?raw=true)
* Mon Dec 30 03:20:52 UTC 2019 - dependabot/npm_and_yarn/node-ui/render-process/handlebars-4.5.3 (linux) - Failed: [generated-linux.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/handlebars-4.5.3/generated-linux.tar.gz?raw=true)
* Mon Dec 30 03:12:13 UTC 2019 - dependabot/npm_and_yarn/node-ui/render-process/handlebars-4.5.3 (mac) - Failed: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/dependabot/npm_and_yarn/node-ui/render-process/handlebars-4.5.3/generated-mac.tar.gz?raw=true)
* Tue Oct 15 03:44:55 UTC 2019 - refs/heads/master (windows) - Succeeded: [generated-windows.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/heads/master/generated-windows.tar.gz?raw=true)
* Sat Oct 12 03:06:30 UTC 2019 - refs/tags/v1.0.0 (windows) - Succeeded: [generated-windows.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/tags/v1.0.0/generated-windows.tar.gz?raw=true)
* Sat Oct 12 02:39:12 UTC 2019 - refs/tags/v1.0.0 (mac) - Succeeded: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/tags/v1.0.0/generated-mac.tar.gz?raw=true)
* Fri Oct 11 20:29:54 UTC 2019 - refs/heads/master (linux) - Failed: [generated-linux.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/heads/master/generated-linux.tar.gz?raw=true)
* Wed Oct  9 22:23:50 UTC 2019 - refs/tags/v1.0.0-rc.4 (windows) - Succeeded: [generated-windows.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/tags/v1.0.0-rc.4/generated-windows.tar.gz?raw=true)
* Wed Oct  9 22:21:53 UTC 2019 - refs/tags/v1.0.0-rc.4 (linux) - Succeeded: [generated-linux.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/tags/v1.0.0-rc.4/generated-linux.tar.gz?raw=true)
* Wed Oct  9 22:03:14 UTC 2019 - refs/tags/v1.0.0-rc.4 (mac) - Succeeded: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/refs/tags/v1.0.0-rc.4/generated-mac.tar.gz?raw=true)
* Sat Oct  5 04:26:46 UTC 2019 - GH-205 (linux) - Succeeded: [generated-linux.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/GH-205/generated-linux.tar.gz?raw=true)
* Sat Oct  5 03:33:11 UTC 2019 - GH-205 (windows) - Succeeded: [generated-windows.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/GH-205/generated-windows.tar.gz?raw=true)
* Sat Oct  5 03:18:26 UTC 2019 - GH-205 (mac) - Succeeded: [generated-mac.tar.gz](https://github.com/substratum-temporary/SubstratumNode-results/blob/master/results/GH-205/generated-mac.tar.gz?raw=true)
