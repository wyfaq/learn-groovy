#!/usr/bin/env groovy
@Library('my-share-library') import org.foo.*

def utils = new Utilities(steps)
def z = new Zot()

node ('jenkins-slave-01'){
  z.checkOutFrom('http://git.quarkfinance.com/payday-loan/bizappForNDes.git')
  utils.mvn 'clean package'
}