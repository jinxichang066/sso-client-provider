# sso-client 代码


####sso-client-provider项目打成jar包
- 进入sso-client-provider项目下，先清空target：mvn clean
- 打包：mvn package -DskipTests=true
- 生成sso-client-jar-with-dependencies.jar，提供给第三方系统集成