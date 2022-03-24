# freeCodeCamp-Tasks
放置在FCC上做的任务


## 响应式网页设计

### Tribute Page

FCC例子：https://codepen.io/freeCodeCamp/full/zNqgVx

- **需求 1：** 此 app 中应存在一个 `id="main"` 的元素，页面上的所有元素都应置于这个元素中。
- **需求 2：** 此 app 中应存在一个 `id="title"` 的元素，其中包含描述致敬页主题的字符串文本，如 "Dr. Norman Borlaug"。
- **需求 3：** 此 app 中应存在一个 `id="img-div"` 的 `figure` 或 `div` 元素。
- **需求 4：** 在 `img-div` 元素内，应存在一个 `id="image"` 的 `img` 元素。
- **需求 5：** 在 `img-div` 元素内，应存在一个相应的 `id="img-caption"` 的元素，其中包含对 `img-div` 中图像的描述文本。
- **需求 6：** 此 app 中应存在一个 `id="tribute-info"` 的元素，其中应包含描述致敬页主题的内容文本。
- **需求 7：** 此 app 中应存在一个 `id="tribute-link"` 的 `a` 元素，它应链接到一个包含有关致敬页主题额外信息的外部网页。 提示：你必须为 a 元素提供 `target` 属性，并将其属性值设置为 `_blank`（即 `target="_blank"`），这样才可以在新选项卡中打开链接。
- **需求 8：** `img` 元素应相对于其父元素的宽度自动调整大小，但不超过图片的原始大小。
- **需求 9：** `img` 应在其父元素内居中。

------

### Survey Form

FCC例子：https://codepen.io/freeCodeCamp/full/VPaoNP

- **需求 1：** 此 app 中应存在一个 `id="title"` 的大小为 H1 的标题。
- **需求 2：** 此 app 中应存在一段 `id="description"` 的大小为 P 的短小的描述。
- **需求 3：** 此 app 中应存在一个 `id="survey-form"` 的 `form` 元素。
- **需求 4：** 在表单元素内，应存在 `id="name"` 的输入框（必填项），以便用户输入姓名。
- **需求 5：** 在表单元素内，应存在 `id="email"` 的输入框（必填项），以便用户输入邮箱。
- **需求 6：** 如果用户输入了格式不正确的邮箱，则应出现来自 HTML5 表单数据校验的错误信息。
- **需求 7：** 在表单内，用户应可以在 `id="number"` 的输入框中输入数字。
- **需求 8：** 如果用户在数字输入框内输入非数字内容，则应出现来自 HTML5 表单数据校验的错误信息。
- **需求 9：** 如果用户输入的数字超出了使用 `min` 和 `max` 属性定义的范围，则应出现来自 HTML5 表单数据校验的错误信息。
- **需求 10：** 表单中的姓名、邮箱和数字输入框需有对应的包含描述输入框用途的标签。这些标签的 id 应分别为 `id="name-label"`、`id="email-label"` 和 `id="number-label"`。
- **需求 11：** 表单中的姓名、邮箱和数字输入框需有对应的描述文字作为占位符。
- **需求 12：** 在表单元素内，应存在一个 `id="dropdown"` 的下拉列表，用户可以从中选取一个选项。
- **需求 13：** 在表单元素内，应至少存在一组单选按钮，用户可以从中选取一个选项。 每组应使用 `name` 属性进行分组。
- **需求 14：** 在表单元素内，应存在几个复选框，且每个复选框都应有 `value` 属性。
- **需求 15：** 在表单元素的最后，应存在一个 `textarea` 元素，以便用户输入额外的批注。
- **需求 16：** 在表单元素内，应存在一个 `id="submit"` 的按钮，以便用户提交表单。

------

### Product Landing Page

例子：https://codepen.io/freeCodeCamp/full/RKRbwL

- **需求 1：** 产品登录页应存在 `id="header"` 的 `header` 元素。
- **需求 2：** 在 `header` 元素内应存在 `id="header-img"` 的图像， 这里通常用来放置公司的 logo。
- **需求 3：** 在 `#header` 元素内，应存在一个 `id="nav-bar"` 的 `nav` 元素。
- **需求 4：** `nav` 元素中应至少包含三个 class 为 `nav-link` 且可点击的元素。
- **需求 5：** 当点击 `nav` 内的 `.nav-link` 按钮时，应滚动到产品主页上相应的部分。
- **需求 6：** 页面上应存在 `id="video"` 的嵌入式视频播放区域。
- **需求 7：** 产品登陆页应存在一个 `id="form"` 的 `form` 元素。
- **需求 8：** 在表单中，应存在一个 `id="email"` 的 `input` 输入框供用户填写邮箱。
- **需求 9：** `#email` 输入框内应存在描述该区域用途的占位符文字。
- **需求 10：** `#email` 输入框应使用 HTML5 验证来确认输入的内容是否为邮箱。
- **需求 11：** 在表单中，应存在一个 `id="submit"` 的 `input` 提交按钮。
- **需求 12：** 当点击 `#submit` 元素时，应将邮箱信息提交到一个静态页面（请使用这个模拟的 URL：https://www.freecodecamp.com/email-submit）。
- **需求 13：** navbar 应保持在视口（viewport）的顶部。
- **需求 14：** 在此 app 中，应至少使用一次媒体查询。
- **需求 15：** 在此 app 中，应至少使用一次 CSS 的 flexbox 布局。

------

### Technical Documentation Page

例子：https://codepen.io/freeCodeCamp/full/NdrKKL

- **需求 1：** 此 app 中应存在一个 `id="main-doc"` 的 `main` 元素，它包含页面的主要内容（技术文档）。
- **需求 2：** 在 `#main-doc` 元素内，应有一些 `section` 元素，每个元素的 class 都应为 `main-section`。 应存在至少 5 个这样的元素。
- **需求 3：** 每个 `.main-section` 内的第一个元素应为 `header` 元素，其中包含描述该部分主题的内容文本。
- **需求 4：** 类名为 `main-section` 的每个 `section` 元素都应有一个与包含在其中的每个 `header` 的文本相对应的 id， 所有空格都应该被替换为下划线（例如，包含标题 “JavaScript and Java” 的 `section` 应有一个相应的 `id="JavaScript_and_Java"`）。
- **需求 5：** 所有 `.main-section` 元素内总计应有至少 10 个 `p` 元素。
- **需求 6：** 所有 `.main-section` 元素内总计应有至少 5 个 `code` 元素。
- **需求 7：** 所有 `.main-section` 元素内总计应有至少 5 个 `li` 元素。
- **需求 8：** 此 app 中应存在一个 `id="navbar"` 的 `nav` 元素。
- **需求 9：** navbar 元素内应有一个 `header` 元素，其中包含描述技术文档主题的内容文本。
- **需求 10：** 此外，navbar 元素应包含 class 为 `nav-link` 的 `a` 元素， 每个 class 为 `main-section` 的元素都需要有一个。
- **需求 11：** navbar 中的 `header` 元素应置于 navbar 中所有 `a` 元素之前。
- **需求 12：** 所有 class 为 `nav-link` 的元素都需要包含与 `section` 中 `header` 相应的内容文本。例如，对于一个文本为 "Hello world" 的一节或标题，你的 navbar 中也应存在一个内容文本为 "Hello world" 的元素。
- **需求 13：** 当点击 navbar 中一个元素时，页面应滚动到 `main-doc` 中的相应部分。例如，点击文本为 "Hello world" 的 `nav-link` 元素的时候，页面应滚动到包含相同内容的 `header` 和 id 所处的 `section` 元素。
- **需求 14：** 在常规尺寸的设备上（如笔记本电脑和台式机），`id="navbar"` 的元素应显示在屏幕左侧，且始终对用户可见。
- **需求 15：** 在此 app 中，应至少使用一次媒体查询。

------

Personal Portfolio Webpage

例子：https://codepen.io/freeCodeCamp/full/zNBOYG

- **需求 1：** 此 app 中应存在一个 id 为 `welcome-section` 的欢迎区。
- **需求 2：** 欢迎区内应存在一个包含标题文本的 `h1` 元素。
- **需求 3：** 此 app 中应存在一个 id 为 `projects` 的项目展示区。
- **需求 4：** 项目展示区应至少包含一个 class 为 `project-tile` 的元素来展示项目。
- **需求 5：** 项目展示区应至少包含一个链接到项目的超链接元素。
- **需求 6：** 此 app 中应存在一个 id 为 `navbar` 的导航栏。
- **需求 7：** 导航栏中应包含一个可以滚动到本页面不同区域的链接。
- **需求 8：** 此 app 中应包含一个 id 为 `profile-link` 的链接。 点击这个链接时，它应在浏览器的新标签页内打开我的 GitHub 或者 FCC 作品集页面。
- **需求 9：** 在此 app 中，应至少使用一次媒体查询。
- **需求 10：** 欢迎区的高度应该与视口的高度保持一致。
- **需求 11：** 导航栏应始终保持在视口顶部。
