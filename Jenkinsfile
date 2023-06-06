pipeline 
{
    agent any

    stages 
    {
        stage('Inicio') 
        {
            steps 
            {
                echo 'Inicio proceso jenkins!'
            }
        }
        stage('Mover archivo') 
        {
           bat 'move "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\PPL_8\\Jenkinsfile" "C:\\"'
        }
    }
}
