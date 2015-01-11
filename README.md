# Dumpling Plugin for Jenkins

Dumpling plugin for Jenkins brings [Dumpling DSL](https://github.com/olivergondza/dumpling) capabilities into Jenkins.

It can be used as an API plugin used by other plugin interested in Jenkins thread monitoring or most importantly, from groovy scripts.

Plugin exposes `Dumpling` class to facilitate access from scripts. Install plugin and use dumpling as easily as:


    Dumpling.runtime.threads.grep { it.name.startsWith('Executor') }

More useful scripts on [wiki](https://wiki.jenkins-ci.org/display/JENKINS/Dumpling+Plugin#DumplingPlugin-Usefulscripts).
