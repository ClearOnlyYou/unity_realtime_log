# unity-realtime-log

Unity realtime log in command line (batchmode)

## Why this?

Unity commnad line batch mode has one problem,

It cannot print the log realtime.

So this Python script use `subprocess` and `thread` to call Unity batch mode and print the log realtime.


## Use

On Windows:

```shell
unity_realtime_log.bat -unity C:\Unity\Unity.exe -project C:\UnityProjectPath -method GameEditor.BuildMethod
```


On Mac:

```shell
unity_realtime_log.sh -unity /Applications/Unity/Unity.app/Contents/MacOS/Unity -project ~/UnityProjectPath -method GameEditor.BuildMethod
```


Or Python:

```shell
python unity.py -unity C:\Unity\Unity.exe -project C:\UnityProjectPath -method GameEditor.BuildMethod
```
//新加jenkens命令行打包apk
E:
cd E:\Raramagi\RaramagiClient
git fetch -p --all
git checkout "update/2.7.3.2"
git pull
git merge origin/develop -m "merge develop branch" -X ours
git push origin "update/2.7.3.2

E:\Raramagi\unity_realtime_log\unity_realtime_log.bat -unity E:\Raramagi\soft\Unity5.3.6f1\Editor\Unity.exe -project E:\Raramagi\RaramagiClient -method BuildBatchScript.BuildForAndroidApk
