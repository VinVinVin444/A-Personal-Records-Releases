# A-Personal-Records

个人记录与生活数据工作台，在一个界面中集中管理个人资料、物品、关系、账单、使用记录与可视化关系画板。

## 主要功能

- 使用分类、分组和卡片整理身体记录、社交关系、物品与生活内容。
- 提供普通、封面和图文三种卡片视图，并支持卡片属性、金额条目、使用记录和附件管理。
- 记录日常收支、周期续费和永久记录，支持月份、收支、分组、颜色、排序与分页等查看方式。
- 使用游戏化关系画板展示小岛、人物、关系、生活、工作和房间中的数据节点。
- 支持节点选择、拖动、位置保存、房间预览、属性抽屉和自定义关系连线。
- 支持亮色、深色与小岛主题，并提供 Banner、分区聚焦和底部定位工具栏。
- 业务数据主要使用 Vault 内的 Markdown 与 JSON 文件，便于随 Vault 备份和同步。

## 付费与激活

A-Personal-Records 是需要购买许可证并激活后使用完整功能的付费插件。未激活时显示激活界面，可输入激活码或进入插件设置完成激活。

激活码请通过作者的正式销售或联系渠道获取：

- [购买 A-Personal-Records 激活码](https://wzyp.cn/shop/NIAR958A)
- QQ群：603045364
- 微信：VinVinVin444
- [Bilibili](https://space.bilibili.com/3493128231193555)
- [小红书](https://xhslink.cn/m/8ZWjZpJc6sK)
- [抖音](https://v.douyin.com/bqTGipbnW_8/)

## 网络访问

A-Personal-Records 只在下列场景访问网络：

1. 激活许可证，以及许可证需要在线验证、续签或恢复时连接授权服务器。
2. 用户主动检查或下载第四分区的可选节点插画资源时访问公开 GitHub 发行仓库。
3. 用户主动使用封面 URL 下载功能时访问其填写的图片地址。
4. 用户主动打开搜索、购买页面或作者资料等外部链接。

授权服务可能接收激活或验证所必需的数据类别：激活码（仅激活时）、产品代码、匿名设备 ID、设备名称与平台信息，以及验证所需的离线许可证。可选插画下载器只下载静态 PNG 资源，不下载或执行远程代码。

## 隐私

- 无客户端行为遥测。
- 无使用行为分析。
- 无广告跟踪。
- 不出售用户数据。
- 不向 GitHub 上传 Vault 笔记或个人记录。

完整说明见 [PRIVACY.md](./PRIVACY.md)。

## 数据与备份

业务数据主要保存在当前 Vault 的 `A_PersonalRecords_Data` 目录；插件设置和离线许可证保存在当前 Vault 的插件配置数据中；匿名设备 ID 保存在当前 Vault 配置目录下的 `a-license/device.json`。

插件内自动下载的节点插画保存在 `A_PersonalRecords_Data/000_Config/resources/node-illustrations`。用户也可以把插画手动放入 `.obsidian/plugins/a-personal-records/assets/node-illustrations/`。

备份整个 Vault 时，上述业务数据会一并备份。卸载插件不会自动删除用户的 Markdown 记录或已下载资源。跨设备同步插件配置目录时，每个授权设备仍受许可证设备数量限制。

## 安装与更新

正式上架后，请通过 Obsidian Community Plugin Directory 安装和更新。不要从非官方来源下载修改过的构建文件。

节点插画属于可选静态资源，可在第四分区的画板资源管理器中下载，也可以根据界面教程手动安装。

## Source and review

A-Personal-Records is a paid, license-activated plugin. Its complete TypeScript source code is maintained in a private repository. Release builds are submitted to the Obsidian Community Directory review and scanning process.

The plugin connects to its licensing service only for activation and license validation. Optional illustration downloads contain static PNG files only. A-Personal-Records contains no client telemetry, usage analytics, or advertising trackers.

## Third-party software

This plugin uses Cytoscape.js, licensed under the MIT License. Complete notices are available in [THIRD_PARTY_LICENSES.md](./THIRD_PARTY_LICENSES.md).

## Support

作者：全平台：岛民Vin。问题反馈与购买咨询可通过上述作者渠道联系。

## License

A-Personal-Records is proprietary commercial software distributed under the terms in [LICENSE](./LICENSE). Third-party components remain governed by their respective licenses.
