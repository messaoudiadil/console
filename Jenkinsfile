node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
	//	bat 'nuget restore ConsoleApp1.sln'
		bat ""C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\MSBuild\15.0\Bin\msbuild.exe" ConsoleApp1.sln /p:Configuration=Release /p:Platform=\"Any CPU\" /p:ProductVersion=1.0.0.${env.BUILD_NUMBER}"

	//stage 'Archive'
		//archive 'ProjectName/bin/Release/**'

}