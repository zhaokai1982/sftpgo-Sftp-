# SFTPGo

[![CI Status](https://github.com/drakkan/sftpgo/workflows/CI/badge.svg)](https://github.com/drakkan/sftpgo/workflows/CI/badge.svg)
[![许可证: AGPL-3.0-only](https://img.shields.io/badge/License-AGPLv3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Mentioned in Awesome Go](https://awesome.re/mentioned-badge.svg)](https://github.com/avelino/awesome-go)

功能齐全、高度可配置的事件驱动文件传输解决方案.
服务器协议：SFTP、HTTP/S、FTP/S、WebDAV.
存储后端：本地文件系统、加密本地文件系统，S3（兼容）对象存储，Google云存储，Azure Blob存储，其他SFTP服务器.

使用SFTPGo，您可以利用本地和云存储后端，使用您已经熟悉的相同工具和流程，在内部或与业务合作伙伴交换和存储文件.

Web管理UI允许轻松创建和管理您的用户、文件夹、组和其他资源.

Web客户端UI允许最终用户更改其凭据，在浏览器中浏览和管理其文件，并设置与Microsoft身份验证器、谷歌认证、Authy 和其他兼容应用程序配合使用的双重身份验证.

## 赞助人

我们坚信开源软件模式，所以我们决定让每个人都能使用SFTPGo，但维护和发展SFTPGo需要大量的时间和工作。为了使开发和维护可持续，你应该考虑用[sponsorship](https://github.com/sponsors/drakkan).

我们喜欢做这项工作，并希望继续做下去——您的支持有助于实现SFTPGo.

重要的是要明白，你应该支持SFTPGo和你依赖的任何其他开源项目进行持续维护，即使你没有任何问题或需要新功能，以降低你依赖的项目无法维护的业务风险，及其安全性和开发速度的影响。

### 感谢我们的赞助商

#### Platinum sponsors

[<img src="./img/Aledade_logo.png" alt="Aledade logo" width="202" height="70">](https://www.aledade.com/)
</br></br>
[<img src="./img/jumptrading.png" alt="Jump Trading logo" width="362" height="63">](https://www.jumptrading.com/)
</br></br>
[<img src="./img/wpengine.png" alt="WP Engine logo" width="331" height="63">](https://wpengine.com/)

#### Silver sponsors

[<img src="./img/IDCS.png" alt="IDCS logo" width="212" height="51">](https://idcs.ip-paris.fr/)

#### Bronze sponsors

[<img src="./img/7digital.png" alt="7digital logo" width="178" height="56">](https://www.7digital.com/)
</br></br>
[<img src="./img/servinga.png" alt="servinga logo" width="258" height="56">](https://servinga.com/)
</br></br>
[<img src="./img/reui.png" alt="ReUI logo" width="151" height="56">](https://www.reui.io/)

## Support

You can use SFTPGo for free, respecting the obligations of the Open Source [license](#license), but please do not ask or expect free support as well.

Use [discussions](https://github.com/drakkan/sftpgo/discussions) to ask questions and get support from the community.

We offer commercial support, guarantees, and advice for SFTPGo:

- With our [plans](https://sftpgo.com/plans) you can safely install and use SFTPGo on-premise in professional environments.
- With our [SaaS offerings](https://sftpgo.com/saas) you can use SFTPGo hosted in the cloud, fully managed and supported.

## Documentation

You can read more about supported features and documentation at [docs.sftpgo.com](https://docs.sftpgo.com/).

## Internationalization

The translations are available via [Crowdin](https://crowdin.com/project/sftpgo), who have granted us an open source license.

Before start translating please take a look at our contribution [guidelines](https://sftpgo.github.io/latest/web-interfaces/#internationalization).

## Release Cadence

SFTPGo releases are feature-driven, we don't have a fixed time based schedule. As a rough estimate, you can expect 1 or 2 new major releases per year and several bug fix releases.

## Acknowledgements

SFTPGo makes use of the third party libraries listed inside [go.mod](./go.mod).

We are very grateful to all the people who contributed with ideas and/or pull requests.

Thank you to [ysura](https://www.ysura.com/) for granting us stable access to a test AWS S3 account.

Thank you to [KeenThemes](https://keenthemes.com/) for granting us a custom license to use their amazing [themes](https://keenthemes.com/bootstrap-templates) for the SFTPGo WebAdmin and WebClient user interfaces, across both the Open Source and Open Core versions.

Thank you to [Crowdin](https://crowdin.com/) for granting us an Open Source License.

Thank you to [Incode](https://www.incode.it/) for helping us to improve the UI/UX.

## License

SFTPGo source code is licensed under the GNU AGPL-3.0-only with [additional terms](./NOTICE).

The [theme](https://keenthemes.com/bootstrap-templates) used in WebAdmin and WebClient user interfaces is proprietary, this means:

- KeenThemes HTML/CSS/JS components are allowed for use only within the SFTPGo product and restricted to be used in a resealable HTML template that can compete with KeenThemes products anyhow.
- The SFTPGo WebAdmin and WebClient user interfaces (HTML, CSS and JS components) based on this theme are allowed for use only within the SFTPGo product and therefore cannot be used in derivative works/products without an explicit grant from the [SFTPGo Team](mailto:support@sftpgo.com).

More information about [compliance](https://sftpgo.com/compliance.html).

## Copyright

Copyright (C) 2019 - 2025 Nicola Murino
