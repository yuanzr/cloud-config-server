# cloud-config-server:
存放的配置文件必须的格式规范:config-client-xxx.properties;/
config-client中通过xxx配置引用:spring.cloud.config.profile=xxx;/
config-server中:spring.cloud.config.server.git.searchPaths=cloud-config-server;/
                searchPaths必须是git的仓库名开头cloud-config-server/xxx/xxx;
