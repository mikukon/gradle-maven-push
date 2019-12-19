# gradle-maven-push

#option 可选项, 默认会从ext中读取，如果这边设置了，会优先使用自定义配置

#require 必选项, 必须配置

#require
GroupId=me.jayi.test
#require
ArtifactId=lib_oss
#require
ReleaseVersionName=1.0.0
#require
SnapShotVersionName=1.0.0-SNAPSHOT

#option
ReleaseUrl=file:///Users/amos/localMaven
#option
SnapShotUrl=file:///Users/amos/localSnapShot
#option
Username=mikukon
#option
Password=123456aa
#option
isBuildRelease=false
