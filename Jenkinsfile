pipeline{
  agent any
  stages{
    stage("Access Jira"){
      agent any
      steps{
        jiraComment body: 'Test', issuekey: 'TEST'
      }
    }
  }
}
