pipeline {
				agent any
				stages {
					stage('BUILD') {
            agent{label 'ubuntu'}
						steps {
							sh '''
								pwd
								sleep 5
								echo This is the fist stage: BUILD
							'''
						}	
					}
					
					stage('TEST') {
            agent{label 'ubuntu2'}
						steps {
							sh '''
								pwd
								sleep 5
								echo This is the fist stage: TEST
							'''
						}	
					}
					
					stage('DEPLOY') {
						steps {
              agent{label 'ubuntu'}
							sh '''
								pwd
								sleep 5
								echo This is the fist stage: DEPLOY
							'''
						}	
					}
				}
			}
		Docker 	
