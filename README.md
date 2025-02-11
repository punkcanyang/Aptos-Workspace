# Aptos-Workspace



提交任务时使用的 Aptos 钱包地址:

0x0ea8d82fd682bfe97c8b236e6711ff81854c6504b640d24621328f3a04c7105a
运行结果
Exception during run: TypeError [ERR_UNKNOWN_FILE_EXTENSION]: Unknown file extension ".ts" for /Users/punkcan/Documents/GitHub/Aptos-Workspace/tests/my-first-test.ts
at Object.getFileProtocolModuleFormat [as file:] (node:internal/modules/esm/get_format:176:9)
at defaultGetFormat (node:internal/modules/esm/get_format:219:36)
at defaultLoad (node:internal/modules/esm/load:143:22)
at async ModuleLoader.load (node:internal/modules/esm/loader:555:7)
at async ModuleLoader.moduleProvider (node:internal/modules/esm/loader:434:45)
at async link (node:internal/modules/esm/module_job:87:21) {
code: 'ERR_UNKNOWN_FILE_EXTENSION'
}

进程已结束，退出代码为 1


使用体验：

- 不支援Podman，工程师修改中
- Aptos 要更新到最新版本才能正常运作，建议将更新版本放到Script中
- 测试时出现 Error: Cannot find module 'ts-node/register'，但是已有这个包，需要手动指定路径 ./node_modules/ts-node/
-
使用反馈:

- 暂时还没法直接用mocha发布