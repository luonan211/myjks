pipeline{
	agent any
	parameters{
		booleanParam(defaultValue:true, description:"test parameters", name: "userFlag")
	}
	stages{
		stage("Build"){
			steps{
			sh "printenv"   //将环境变量打印到控制台
			}
		}
		stage("Test"){
			steps{
			echo "TestFlag: ${params.userFlag}"
			}
		}
	}
}
