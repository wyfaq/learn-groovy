#!/usr/bin/env groovy
@Library('my-share-library') _
node {
  stage('First stage') {
    dockerFingerprintFrom([image: "172.30.33.31:5000/quark/dac_tsp"])
  }
}
