//node {
//	stage 'Checkout'
//		checkout scm
//
//	stage 'Build'
//	//	bat 'nuget restore ConsoleApp1.sl
//bat '"C:\\Program Files (x86)\\Microsoft Visual Studio\\2017\\Community\\MSBuild\\15.0\\Bin\\msbuild.exe" ConsoleApp1.sln /p:Configuration=Release /p:Platform="Any CPU"'
//	//stage 'Archive'
//		//archive 'ProjectName/bin/Release/**'
//
//}



stage('Build') {
msbuild project: 'ConsoleApp1/ConsoleApp1.csproj', target: 'Restore,Build',
properties: [  SolutionDir: "${env.WORKSPACE}/" ]

}