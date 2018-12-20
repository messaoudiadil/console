node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
	//	bat 'nuget restore ConsoleApp1.sln
bat 'msbuild.exe ConsoleApp1.sln /p:Configuration=Release /p:Platform="Any CPU"'
	//stage 'Archive'
		//archive 'ProjectName/bin/Release/**'

}




//job('example') {
//    steps {
//        msBuild {
//            msBuildInstallation('MSBuild')
//            buildFile('ConsoleApp1/ConsoleApp1.csproj')
//            args('check')
//            args('another')
//            passBuildVariables()
//            continueOnBuildFailure()
//            unstableIfWarnings()
//        }
//    }
//}