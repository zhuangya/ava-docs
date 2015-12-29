# 维护


## 测试

 - `npm test`: 检查语法，以及运行所有的测试案例以及测试覆盖率。
 - `npm run test-win`: 运行 Windows 上的测试。
 - `npm run coverage`: 针对最后一次测试生成测试覆盖率报告（会打开浏览器）
 - `tap test/fork.js --bail`: 针对某个文件测试，并且会停留在第一次出错的地方（找 bug 的时候非常有用）。


## 发布流程

- 发布依赖
- 确保 [Travis CI](https://travis-ci.org/sindresorhus/ava) 和 [AppVeyor](https://ci.appveyor.com/project/sindresorhus/ava/branch/master) 都已经通过。
- 使用 [`np`](https://github.com/sindresorhus/np) 发布一个复合 [semver](http://semver.org) 的新版本。
- 依据之前的分割写 [发布说明](https://github.com/sindresorhus/ava/releases/new)。


## Pull requests

- 新的功能应该带有测试和文档。
- 确保遵循 [贡献准则](contributing.md)
- 合并之前至少两名团队成员必须 `LGTM(我觉得不错)`
- 合并的时候压缩提交。
