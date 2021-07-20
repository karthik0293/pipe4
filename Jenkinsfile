pipeline {
				agent any
				stages {
					stage('BUILD') {
            agent{label1 'ubuntu'}
						steps {
							sh '''
								pwd
								sleep 5
								echo This is the fist stage: BUILD
							'''
						}	
					}
					
					stage('TEST') {
            agent{label2 'ubuntu2'}
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
              agent{label1 'ubuntu'}
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
