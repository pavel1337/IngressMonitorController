#!/usr/bin/env groovy
@Library('github.com/stakater/stakater-pipeline-library@v2.16.33') _

goBuildViaGoReleaser {
    publicChartRepositoryURL = 'https://stakater.github.io/stakater-charts'
    publicChartGitURL = 'git@github.com:stakater/stakater-charts.git'
    toolsImage = 'stakater/pipeline-tools:v2.0.18'
    verify = true
}