# Compare VS2017 and VS2019 build

I noticed a performance degradation between VS2017 and VS 2019 for the same application and same configuration. 

The activity is slower at launch and the apk is bigger.

## Configuration

Platform affected : Android<br/>
Application : Xamarin Forms - Blank template<br/>
TargetFrameworkVersion : v8.1<br/>
Configuration : Release<br/>
AotAssemblies : Enabled<br/>

## Results

Build on Azure pipeline :
https://dev.azure.com/mohamedchouchane0699/VS2017VS2019Compare/_build 

|               |    APK Size   |  Activity Displayed |
| ------------- | ------------- | ------------------- |
| VS 2017       | 24 177 ko     | 1115 ms             |
| VS 2019       | 34 938 ko     | 2455 ms             |

