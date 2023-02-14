pipeline{
	agent any
	tools{
		maven 'mvn-3.8.7'
	}
	stages{
		stage("Build"){
			steps{
			sh "mvn clean package spring-boot:repackage"
			sh "printenv"   //将环境变量打印到控制台
			}
		}
	}
}
