pipeline{
	agent any
	stages{
		stage("SCM"){
			steps{
			   echo " SCM Stage US1"
			}
		}
		stage("BUILD"){
		   when {
			branch 'master'
			}

			steps{
				echo "Params value isabc"
			}
		}
	}
}

