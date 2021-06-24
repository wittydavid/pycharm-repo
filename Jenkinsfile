properties([parameters([string(defaultValue: 'david', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one"){
        git branch: 'main', url: 'https://github.com/wittydavid/pycharm-repo.git'
        sh "cat file1.txt"
    }
}
