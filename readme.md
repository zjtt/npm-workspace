<!-- npm 从版本 7 开始支持 Workspaces 功能 -->
全部依赖都会安装到根目录

有幽灵依赖的问题

<!-- npm install lodash --workspace=packages/package-a -->
<!-- npm run build --workspace=packages/package-a -->

npm init -w ./packages/* 	初始化

npm install packageA -w packageB 	给packageB安装packageA，版本号显示项目中packageA的版本号

npm uninstall packageA -w packageB	卸载packageB中的packageA

npm run build --workspaces	在所有包中运行build命令