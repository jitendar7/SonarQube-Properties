# SonarQube-Properties


sonarqube {
  properties {
    
    property "sonar.projectName", "Name"
    property "sonar.projectKey", "key"
    property "sonar.host.url", "url"
    property "sonar.language", "java"
    property "sonar.sources", "src/main/, src/branch/java"
    property "sonar.login", "b122asdkf2199j11k231"
    property "sonar.password", ""
    property "sonar.projectversion", "some version"
    property "sonar.projectDescription", "project description"
    property "sonar.java.binaries", "build/intermediates/javac/mainDebug/compileDebugJavaWithJavac/classes/"
    property "sonar.tests", "src/test/java , src/testDebug/java"
    property "sonar.exclusions", "**/TestHelper.java , **/Test2Helper.java," + " **/UI.java"
    property "sonar.coverage.exclusions", "**/dialog/**, **/constants/**, "
    property "sonar.java.coveragePlugin", "jacoco"
    property "sonar.jacoco.reportPaths", "build/jacoco/testDebugUnitTest.exec"
    property "sonar.android.lint.report", "build/outputs/lint-results-debug.xml"
    
    property "sonar.issue.ignore.multicriteria","maximumInheritanceBaseActivity"
    
    property "sonar.issue.ignore.multicriteria.maximumInheritanceBaseActivity.ruleKey", "squid:MaximumInheritanceDepth"
    property "sonar.issue.ignore.multicriteria.maximumInheritanceBaseActivity.resourceKey", "**/BaseActivity.java"
    
    
  } 
}
