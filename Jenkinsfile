//node {
//	stage 'Build'
//bat '"C:\\Program Files (x86)\\Microsoft Visual Studio\\2017\\Community\\MSBuild\\15.0\\Bin\\msbuild.exe"
//ConsoleApp1.sln /p:Configuration=Release /p:Platform="Any CPU"'
//}


node {
	stage 'Build'
def msbuild = tool name: 'msbuild'
bat "${msbuild} ConsoleApp1.sln /p:Configuration=Release /p:Platform=\"Any CPU\"  "
}



//stage('Build') {
//msbuild project: 'ConsoleApp1/ConsoleApp1.csproj', target: 'Restore,Build',
//properties: [  SolutionDir: "${env.WORKSPACE}/" ]
//}