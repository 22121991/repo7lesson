properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/22121991/repo7lesson.git'
    }
    stage("show files"){
        bat "dir"
    }
}
