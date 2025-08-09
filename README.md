// ===== 编辑器外观设置 =====
"editor.fontSize": 17, // 编辑器字体大小
"editor.lineHeight": 24, // 编辑器行高
"editor.fontLigatures": true, // 启用字体连字功能
"editor.renderWhitespace": "all", // 显示所有空白字符
"editor.cursorBlinking": "expand", // 光标闪烁动画
"editor.cursorSmoothCaretAnimation": "on", // 启用光标平滑动画
"editor.smoothScrolling": true, // 启用编辑器平滑滚动
"editor.mouseWheelZoom": true, // 启用鼠标滚轮缩放
"editor.minimap.showSlider": "always", // 小地图始终显示滑块
"editor.wordWrap": "on", // 启用文本自动换行
"editor.wordWrapColumn": 120, // 自动换行列数
"editor.accessibilitySupport": "off", // 关闭无障碍功能
"editor.stickyScroll.enabled": true, // 启用粘性滚动
"workbench.list.smoothScrolling": true, // 工作台列表平滑滚动

// ===== 编辑行为设置 =====
"editor.tabSize": 2, // 制表符大小
"editor.detectIndentation": false, // 禁用自动检测缩进
"editor.wordBasedSuggestions": "currentDocument", // 基于当前文档的单词建议

// ===== 代码格式化设置 =====
"editor.defaultFormatter": "esbenp.prettier-vscode", // 默认格式化工具
"editor.formatOnSaveMode": "modificationsIfAvailable", // 保存时只格式化修改内容
"editor.codeActionsOnSave": {
	"source.fixAll.eslint": "explicit",
	"source.fixAll": "explicit",
	"source.organizeImports": "explicit"
}, // 保存时执行代码操作

// ===== Prettier格式化配置 =====
"prettier.trailingComma": "none", // 不添加尾随逗号
"prettier.printWidth": 120, // 每行最大宽度
"prettier.proseWrap": "never", // 不换行处理散文
"prettier.vueIndentScriptAndStyle": false, // Vue文件缩进设置
"prettier.arrowParens": "avoid", // 箭头函数参数括号
"prettier.jsxSingleQuote": true, // JSX使用单引号
"prettier.singleQuote": true, // 使用单引号
"prettier.tabWidth": 4, // 制表符宽度
"prettier.bracketSpacing": true, // 对象括号间距

// ===== 特定文件类型格式化器 =====
"[javascript]": { "editor.defaultFormatter": "vscode.typescript-language-features" },
"[typescript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
"[html]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
"[css]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
"[scss]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
"[json]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
"[vue]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
"[less]": { "editor.defaultFormatter": "vscode.css-language-features" },
"[wxml]": { "editor.defaultFormatter": "qiu8310.minapp-vscode" },

// ===== JavaScript/TypeScript语言设置 =====
"typescript.preferences.importModuleSpecifier": "relative", // 使用相对路径导入
"javascript.preferences.importModuleSpecifier": "relative", // 使用相对路径导入
"javascript.updateImportsOnFileMove.enabled": "always", // 移动文件时更新导入
"javascript.format.insertSpaceBeforeFunctionParenthesis": true, // 函数括号前插入空格
"typescript.updateImportsOnFileMove.enabled": "always", // 移动文件时更新导入
"typescript.validate.enable": false, // 禁用TypeScript验证
"javascript.validate.enable": false, // 禁用JavaScript验证

// ===== 文件管理设置 =====
"files.autoSave": "afterDelay", // 延迟自动保存
"files.autoSaveDelay": 3000, // 自动保存延迟时间
"files.trimTrailingWhitespace": true, // 删除行尾空白
"files.insertFinalNewline": true, // 文件末尾插入新行
"files.associations": { "*.cjson": "jsonc", "*.wxss": "css", "*.wxs": "javascript", "*.jsp": "html" }, // 文件关联配置

// ===== 工作台界面设置 =====
"workbench.colorTheme": "Monokai", // 主题
"window.commandCenter": false, // 隐藏命令中心

// ===== 资源管理器设置 =====
"explorer.confirmDragAndDrop": false, // 拖放时不确认
"explorer.confirmDelete": false, // 删除时不确认

// ===== Git版本控制设置 =====
"git.ignoreMissingGitWarning": true, // 忽略Git缺失警告
"git.autofetch": true, // 自动获取远程更新

// ===== 终端设置 =====
"terminal.integrated.defaultProfile.windows": "PowerShell", // Windows默认终端

// ===== 小程序开发相关 =====
"minapp-vscode.disableAutoConfig": true, // 禁用小程序自动配置

// ===== AI编程助手 =====
"Codegeex.Privacy": true, // CodeGeeX隐私模式
"Codegeex.License": "", // CodeGeeX许可证

// ===== 国际化插件配置 =====
"i18n-ally.localesPaths": ["src/locales"], // 国际化文件路径
"i18n-ally.enabledFrameworks": ["react"], // 启用React框架
"i18n-ally.enabledParsers": ["js", "ts", "json"], // 启用解析器
"i18n-ally.keystyle": "flat", // 键名风格
"i18n-ally.sourceLanguage": "zh-CN", // 源语言
"i18n-ally.displayLanguage": "zh-CN", // 显示语言
"i18n-ally.sortKeys": true, // 键名排序
"i18n-ally.keepFulfilled": true, // 保持已完成翻译

// ===== 搜索设置 =====
"search.exclude": { "**/node_modules": true, "**/bower_components": true, "**/*.code-search": true }, // 搜索排除项
"search.globalFindClipboard": false, // 不使用剪贴板内容

// ===== 性能优化设置 =====
"workbench.enableExperiments": false, // 禁用实验功能
"telemetry.telemetryLevel": "off", // 关闭遥测
"update.enableWindowsBackgroundUpdates": false, // 禁用后台更新
"files.watcherExclude": {
	"**/.git/objects/**": true,
	"**/.git/subtree-cache/**": true,
	"**/node_modules/*/**": true
}, // 文件监视器排除项

// ===== 集成终端增强 =====
"terminal.integrated.fontSize": 14, // 终端字体大小
"terminal.integrated.fontFamily": "'JetBrains Mono', 'Fira Code', Consolas, monospace", // 终端字体
"terminal.integrated.copyOnSelection": true, // 选中时复制
"terminal.integrated.rightClickBehavior": "copyPaste", // 右键复制粘贴
"terminal.integrated.scrollback": 10000, // 滚动缓冲区

// ===== 主题和图标 =====
"workbench.iconTheme": "vscode-icons", // 图标主题

// ===== Emmet扩展配置 =====
"emmet.includeLanguages": { "wxml": "html", "javascript": "javascriptreact", "typescript": "typescriptreact" } // Emmet语言映射