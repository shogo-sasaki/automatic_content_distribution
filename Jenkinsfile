
pipeline {
   agent any
   stages {
     stage('�r���h') {
         steps {
           echo 'Start build'
         }
     }
     stage('�e�X�g') {
       steps {
         writeFile encoding: 'UTF-8', file: 'out.txt', text: 'testtest'
       }
     }
     stage('�����[�X') {
       steps {
         input "���s���܂����H"
         echo '����'
       }
     }
   }
}