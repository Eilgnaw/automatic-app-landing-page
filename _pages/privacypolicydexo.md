---
layout: page
title: Dexo 隐私政策
include_in_header: false
---

# Dexo 隐私政策 / Privacy Policy

**最后更新日期 / Last Updated:** 2026-09-12

---

## 中文版本

### 一、关于本政策

Dexo 是由 Eilgnaw 提供的 iPhone 和 iPad 原生 Discourse 论坛客户端。本政策说明 Dexo 及我们提供的配套服务如何处理信息，以及您可以如何管理这些信息。

Dexo 不要求您注册独立的 Dexo 账号。公开内容通常可以直接浏览；登录、发帖、私信等功能使用您在相应论坛的账号。您访问的论坛由各自的运营者管理，其账号、内容和服务还适用该论坛的隐私政策。Dexo 并非 Discourse 或所连接论坛的官方产品。

### 二、我们处理的信息及用途

#### 2.1 论坛配置、账号与登录状态

为了连接论坛、维持登录和显示内容，Dexo 会在设备上保存论坛地址、名称、排序、用户名、登录状态和应用偏好。登录凭据包括论坛授权的 API Key，或网页登录产生的会话 Cookie；相关数据保存在设备钥匙串、应用存储或系统网页存储中。

网页登录时，您输入的账号信息由相应论坛及其登录服务处理。Dexo 使用授权凭据向对应论坛发送请求，不将论坛密码、API Key 或登录 Cookie 上传到我们的反馈服务或推送中继。

#### 2.2 浏览、搜索与社区互动

浏览话题、搜索、查看通知或个人资料时，Dexo 会向您访问的论坛请求相关内容。发帖、回复、点赞、收藏、发送私信或上传图片时，相应内容和操作会发送到该论坛，并可能与您的论坛账号关联。图片可能在编辑器中选择后即开始上传，即使您最终没有发布帖子。

公开帖子可被其他人访问。私信的存储、访问权限和保留规则由论坛运营者管理，并不因为通过 Dexo 发送而变成仅保存在您设备上的信息。请勿在公开帖子或反馈中提交密码、密钥或不希望公开的信息。

Dexo 还会在设备上保存阅读历史、内容缓存及部分诊断记录。登录后，应用会根据论坛支持情况发送已读状态，以及主题、帖子和阅读时长等信息，用于同步阅读进度和论坛阅读统计。linux.do 的阅读时长上报在符合网页登录条件时默认开启，可在该论坛的阅读上报设置中关闭；其他论坛的账户相关阅读上报可通过退出登录停止。

#### 2.3 推送通知

如果您在支持的论坛启用推送，Dexo 会请求系统通知权限，并使用 Apple 推送通知服务（APNs）。为建立和维护订阅，Dexo 推送中继会处理设备推送令牌、订阅标识、论坛地址、论坛推送公钥及订阅有效期等投递信息。论坛会收到用于向该设备发送通知的订阅端点及必要的订阅参数。

在 Dexo 支持的 Web Push 转发流程中，通知正文以加密形式经中继和 APNs 转发，再由设备上的通知扩展解密显示。中继仍需处理投递信息；这一机制不代表所有论坛帖子或私信都采用端到端加密。设备会保存订阅记录和解密所需的密钥。通知预览是否显示在锁定屏幕上，由您的系统设置决定。

#### 2.4 问题反馈与技术信息

当您打开应用内反馈页面时，Dexo 会向 [反馈服务](https://feedback.umiibo.app/) 传递应用标识、应用版本、系统版本、设备型号、界面语言、主题以及用于关联反馈的应用生成标识符。该标识符不是广告标识符；通常保存在钥匙串中，清理缓存或重新安装后可能仍然保留。在无法保存该标识符时，应用可能使用系统提供的厂商标识符或临时标识符作为替代。

您提交的反馈文字、图片、附件，以及自愿提供的联系方式，会用于回复、跟进和排查问题。这些反馈资料与上述技术信息可能通过同一标识符关联。仅打开反馈页面也会传递上述页面参数，即使您没有提交反馈。

网络请求涉及的论坛、图片或附件服务、反馈服务、推送服务及基础设施提供方，也会在处理连接时接收 IP 地址、请求时间、浏览器或客户端信息等网络元数据，用于提供服务、维护安全和排查故障。

#### 2.5 可选的加密 DNS 与网页功能

启用加密 DNS（DoH）后，您选择的解析服务会处理查询的域名及连接所需的网络信息。其数据处理受该服务的隐私政策约束。关闭 DoH 后，域名解析由系统网络配置处理。

论坛登录页、验证页、内置浏览器及外部链接可能使用 Cookie、网页本地存储、内容分发网络或安全验证服务，例如论坛配置的 Cloudflare 服务。这些服务由相应网站选择和管理；拒绝或清除其会话数据可能使登录或部分网页功能无法使用。

### 三、我们不用于哪些目的

Dexo 不出售个人信息，不使用上述数据进行跨应用或跨网站的广告追踪。Dexo 本身未集成广告追踪或第三方用户行为分析 SDK。

Dexo 不要求提供通讯录、精确位置、麦克风录音或完整照片图库来浏览论坛。您选择上传图片或保存图片时，应用使用相应的系统选择器或权限。第三方网页可能另行请求权限，请根据网页说明和系统提示自行决定。

### 四、信息共享与第三方服务

信息仅在实现所选功能所需的范围内发送给相应接收方：

- **您访问的 Discourse 论坛及其服务提供方**：处理账号、搜索、帖子、私信、附件、阅读状态及论坛通知。
- **Apple**：提供应用分发、系统权限和 APNs 等平台服务。可参阅 [Apple 隐私政策](https://www.apple.com/legal/privacy/)。
- **Dexo 的反馈与推送配套服务及其基础设施提供方**：处理反馈、必要的诊断信息和通知投递。
- **您选择的 DNS 服务或打开的第三方网站**：处理相应的域名查询或网页请求。

我们为配套服务使用服务提供方时，要求其仅为提供相关服务处理必要信息，并采取适当的保密和安全措施。法律要求或为应对安全事件而必要的披露，限于相应目的所需范围。您自行选择的论坛和网站拥有各自的政策，请在使用前查阅。

### 五、存储、保留与安全

论坛配置、偏好、缓存、阅读历史和部分诊断数据主要保存在您的设备上。我们使用 HTTPS 连接论坛和配套服务，并使用设备钥匙串等系统机制保护相应凭据和密钥。互联网传输和电子存储无法保证绝对安全，请保护设备解锁凭据和论坛账号。

本地数据会依其用途保留，直到被更新、清理、删除论坛或移除应用；不同操作处理的数据范围不同。钥匙串中的部分资料可能在卸载后保留。系统备份也可能包含部分应用数据，取决于您的设备和备份设置。

反馈和必要的服务记录按处理问题、维护服务安全以及适用法律要求所需的期限保留。推送路由信息具有有效期，关闭推送或退出账号时应用会尝试取消相关订阅。论坛端的账号、帖子、附件、私信和日志，以及 Apple 或其他独立服务保存的数据，依各自的保留政策处理。服务所在地区可能与您所在地区不同。

### 六、您的选择与删除请求

- **停止账户相关操作**：退出相应论坛；您也可以在论坛网站中撤销 Dexo 的授权或登录会话。
- **管理推送**：在论坛推送设置中关闭订阅，或在 iOS/iPadOS 设置中关闭 Dexo 通知。仅关闭系统通知显示，不等同于删除论坛账号或已经保存的服务端数据。
- **管理阅读与网络功能**：按上述方式关闭 linux.do 阅读上报、退出论坛登录，或关闭 DoH。
- **管理本地数据**：设置中的清理缓存用于清理图片和网络缓存，并不清除全部账号资料或阅读历史。删除论坛或卸载应用也不会删除您在论坛服务器上的账号和发帖内容。
- **管理配套服务中的信息**：如需查询、更正或删除我们控制的反馈及相关个人信息，请通过下方邮箱联系，说明涉及的反馈或请求。我们会在核实请求与相关信息的关联后，依适用要求处理；如有依法必须保留的部分，会说明原因。

论坛账号、帖子和私信的删除，请使用该论坛提供的设置或联系其管理员。Dexo 无法代替独立论坛运营者直接删除这些数据。

### 七、儿童隐私

Dexo 不面向 13 岁以下儿童。使用者还应遵守所在地区的 App Store 年龄分级和所访问论坛的年龄要求。如果您认为儿童向我们的配套服务提供了个人信息，请联系我们，以便核查并处理相关信息。

### 八、政策更新

我们可能因功能或服务变化更新本政策，并在本页注明最新日期。请定期查看；需要另行取得许可的变更，将按适用要求处理。

### 九、联系我们

开发者：Eilgnaw

隐私咨询与数据请求邮箱：[mail@umiibo.app](mailto:mail@umiibo.app)

---

## English Version

### 1. About This Policy

Dexo is a native Discourse client for iPhone and iPad provided by Eilgnaw. This policy explains how Dexo and the supporting services we provide handle information, and how you can manage that information.

Dexo does not require a separate Dexo account. Public content can generally be browsed without signing in; sign-in, posting, and private messaging use your account with the relevant forum. Each forum has its own operator and privacy policy governing its accounts, content, and services. Dexo is not an official product of Discourse or the forums you connect to.

### 2. Information We Process and Why

#### 2.1 Forum Configuration, Accounts, and Sessions

To connect to forums, maintain sessions, and display content, Dexo stores forum addresses, names, ordering, usernames, sign-in state, and app preferences on your device. Credentials include forum-authorized API keys or session cookies created during web sign-in. Relevant information is stored in the device Keychain, app storage, or system web storage.

During web sign-in, the relevant forum and its sign-in providers process the account information you enter. Dexo uses authorized credentials to make requests to the corresponding forum. It does not upload forum passwords, API keys, or sign-in cookies to our feedback service or push relay.

#### 2.2 Browsing, Search, and Community Interaction

When you browse topics, search, or view notifications or profiles, Dexo requests that information from the forum you are visiting. Posts, replies, likes, bookmarks, private messages, image uploads, and related actions are sent to that forum and may be associated with your forum account. Images may begin uploading when selected in the editor, even if you do not ultimately publish a post.

Public posts can be accessed by other people. The forum operator controls the storage, access, and retention of private messages; sending a message through Dexo does not mean it is stored only on your device. Do not include passwords, secret keys, or information you do not wish to disclose in public posts or feedback.

Dexo also stores reading history, cached content, and some diagnostic records locally. When signed in, it sends read status and information such as topic identifiers, post identifiers, and reading durations where supported, to synchronize reading progress and forum reading statistics. For linux.do, reading-duration reporting is enabled by default when the required web session is available and can be turned off in that forum's reporting settings. Signing out stops account-related reading reports for other forums.

#### 2.3 Push Notifications

If you enable push notifications for a supported forum, Dexo requests system notification permission and uses Apple Push Notification service (APNs). To create and maintain subscriptions, the Dexo push relay processes delivery information such as the device push token, subscription identifier, forum address, forum push public key, and subscription expiry. The forum receives a subscription endpoint and the parameters needed to send notifications to the device.

In Dexo's supported Web Push relay flow, notification bodies are forwarded in encrypted form through the relay and APNs and are decrypted by the notification extension on your device. The relay still processes delivery information; this does not mean that all forum posts or private messages are end-to-end encrypted. Subscription records and decryption keys are stored on the device. Your system settings determine whether notification previews appear on the lock screen.

#### 2.4 Feedback and Technical Information

When you open in-app feedback, Dexo sends the app identifier, app version, operating-system version, device model, interface language, theme, and an app-generated feedback identifier to the [feedback service](https://feedback.umiibo.app/). This is not an advertising identifier. It is normally stored in the Keychain and may persist after cache clearing or reinstallation. If it cannot be saved, the app may use the system's vendor identifier or a temporary identifier instead.

Feedback text, images, attachments, and contact details you voluntarily provide are used to respond, follow up, and investigate issues. Feedback and the technical information above may be associated through the same identifier. Opening the feedback page transmits its page parameters even if you do not submit a report.

Forums, image or attachment hosts, feedback and push services, and infrastructure providers also receive network metadata such as IP addresses, request times, and browser or client information when handling connections, to provide services, maintain security, and investigate failures.

#### 2.5 Optional Encrypted DNS and Web Features

If you enable DNS over HTTPS (DoH), the resolver you select processes queried domain names and network information needed for the connection, under its own privacy policy. When DoH is disabled, name resolution follows your system network configuration.

Forum sign-in pages, verification pages, in-app browsing, and external links may use cookies, web storage, content delivery networks, or security services such as a forum's Cloudflare configuration. The relevant website chooses and manages these services. Rejecting or clearing session data may prevent sign-in or other web features from working.

### 3. Purposes We Do Not Use This Information For

Dexo does not sell personal information or use the information described above for advertising tracking across apps or websites. Dexo itself does not integrate advertising-tracking or third-party user-behavior analytics SDKs.

Dexo does not require your contacts, precise location, microphone recordings, or access to your entire photo library to browse forums. Uploading or saving images uses the relevant system picker or permission. Third-party web pages may request their own permissions; review the website's explanation and the system prompt before deciding.

### 4. Sharing and Third-Party Services

Information is sent to the recipients needed for the features you use:

- **The Discourse forums you visit and their providers:** accounts, searches, posts, private messages, attachments, read status, and forum notifications.
- **Apple:** app distribution, system permissions, and platform services such as APNs. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).
- **Dexo's feedback and push services and their infrastructure providers:** feedback, necessary diagnostics, and notification delivery.
- **DNS providers you select and third-party websites you open:** the corresponding DNS queries or web requests.

Where we engage providers for our supporting services, we require them to process necessary information only to provide those services and to apply appropriate confidentiality and security measures. Disclosures required by law or necessary to address security incidents are limited to the relevant purpose. Forums and websites you choose independently have their own policies, which you should review before use.

### 5. Storage, Retention, and Security

Forum configuration, preferences, caches, reading history, and some diagnostics are primarily stored on your device. We use HTTPS for connections to forums and supporting services and system mechanisms such as the device Keychain for relevant credentials and keys. No internet transmission or electronic storage can be guaranteed absolutely secure. Protect access to your device and forum accounts.

Local information is retained for its purpose until it is updated, cleared, removed with a forum, or removed with the app. Different actions affect different data. Some Keychain information may survive uninstallation. System backups may also contain some app data, depending on your device and backup settings.

Feedback and necessary service records are retained for the periods needed to handle issues, maintain service security, and meet applicable legal requirements. Push routing information has an expiry, and the app attempts to cancel relevant subscriptions when push is disabled or an account is signed out. Forum accounts, posts, attachments, private messages, and logs, as well as data held by Apple or other independent services, follow those services' retention policies. Service locations may differ from your location.

### 6. Your Choices and Deletion Requests

- **Stop account-related activity:** sign out of the forum. You can also revoke Dexo's authorization or sessions through the forum website.
- **Manage push:** disable the subscription in the forum's push settings or disable Dexo notifications in iOS/iPadOS Settings. Turning off system notification display alone does not delete a forum account or existing server-side records.
- **Manage reading and networking:** turn off linux.do reading reports as described above, sign out of a forum, or disable DoH.
- **Manage local information:** Clear Cache removes image and network caches; it does not clear all account information or reading history. Removing a forum or uninstalling Dexo does not delete your account or posts on the forum server.
- **Manage information in our supporting services:** to request access, correction, or deletion of feedback and related personal information we control, contact the email below and identify the relevant feedback or request. After verifying the connection between the request and the information, we will handle it in accordance with applicable requirements and explain any legal need to retain part of it.

To delete a forum account, posts, or private messages, use that forum's controls or contact its administrator. Dexo cannot directly delete this information on behalf of an independent forum operator.

### 7. Children's Privacy

Dexo is not directed to children under 13. Users must also meet the applicable App Store age rating and the age requirements of the forums they visit. If you believe a child has provided personal information to our supporting services, contact us so we can investigate and address it.

### 8. Policy Updates

We may update this policy as features or services change and will show the latest date on this page. Please review it periodically. Changes requiring additional permission will be handled in accordance with applicable requirements.

### 9. Contact Us

Developer: Eilgnaw

Privacy inquiries and data requests: [mail@umiibo.app](mailto:mail@umiibo.app)
