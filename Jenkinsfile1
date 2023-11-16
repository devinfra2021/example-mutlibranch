pipeline{
	agent any 
	parameters{
	string(name:'Name', defaultValue: 'this is default value', description:'it is simple name')
	}
	stages{
		stage('Jenkins stage 1'){
		steps{
			sh 'echo ${Name}'
			sh '''
			echo ${Name}
			'''
			sh([script: 'echo ${Name}' ])
		}
		}
	}
}
