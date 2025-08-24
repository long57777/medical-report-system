# 康鑫达医疗报告审核系统

这是一个专业的医疗检测报告审核系统，支持桌面端和移动端访问。

## 在线访问

部署完成后，您可以通过以下链接访问：
- 桌面版：https://yourusername.github.io/repositoryname/index.html
- 移动版：https://yourusername.github.io/repositoryname/mobile-test.html

## 部署到 GitHub Pages 详细步骤

### 1. 创建 GitHub 仓库
1. 访问 https://github.com/
2. 点击右上角的 "+" 号，选择 "New repository"
3. 输入仓库名称，例如：`medical-report-system`
4. 设置为 Public（公开）
5. 点击 "Create repository"

### 2. 上传项目文件
有两种方式上传文件：

#### 方式一：通过网页上传
1. 在新创建的仓库页面，点击 "uploading an existing file"
2. 将以下文件拖拽到页面中：
   - index.html（桌面版）
   - mobile-test.html（移动版）
   - 6812778942107_G09_07.jpg（检测图片）
   - README.md（说明文档）
3. 在底部输入提交信息："Add medical report system"
4. 点击 "Commit changes"

#### 方式二：使用 Git 命令（如果安装了 Git）
```bash
git clone https://github.com/yourusername/repositoryname.git
cd repositoryname
# 复制所有项目文件到这个目录
git add .
git commit -m "Add medical report system"
git push origin main
```

### 3. 启用 GitHub Pages
1. 在仓库页面，点击 "Settings" 选项卡
2. 在左侧菜单中找到 "Pages"
3. 在 "Source" 部分选择 "Deploy from a branch"
4. 选择 "main" 分支
5. 文件夹选择 "/ (root)"
6. 点击 "Save"

### 4. 获取访问链接
几分钟后，GitHub Pages 会提供访问链接：
- 格式：https://yourusername.github.io/repositoryname/
- 桌面版：https://yourusername.github.io/repositoryname/index.html
- 移动版：https://yourusername.github.io/repositoryname/mobile-test.html

## 文件说明

- `index.html` - 桌面端优化版本
- `mobile-test.html` - 移动端优化版本（推荐手机访问）
- `6812778942107_G09_07.jpg` - 检测图谱图片
- `README.md` - 项目说明文档

## 移动端访问优化

移动版（mobile-test.html）包含以下优化：
- 紧凑的布局设计
- 适合手机屏幕的字体大小
- 优化的表格显示
- 响应式图片显示
- 触摸友好的界面

## 技术特性

- 纯HTML/CSS/JavaScript实现
- 使用 Tailwind CSS 框架
- 响应式设计
- 无需服务器环境
- 兼容所有现代浏览器

## 本地开发

如需本地预览：
```bash
python -m http.server 8000
```
然后访问：
- http://localhost:8000/index.html
- http://localhost:8000/mobile-test.html

## 🏥 项目简介

专业的医疗检测报告审核平台，专门用于康鑫达甘达健+糖组六项检测结果的审核和管理。系统完全按照您提供的PNG截图要求设计，包含完整的医疗报告布局和移动端优化。

## 📱 界面特色

### 顶部标题栏
- **左侧**：康鑫达_甘达健+糖组六项结果审核
- **右侧**：收样日期：2025-08-21 | 检测日期：2025-08-22
- **设计**：蓝色背景，专业医疗风格

### 数据表格区域
- **表头**：NO、P1-P9、康鑫达_甘达健+糖组六项计算结果
- **数据**：D2502168_1_A09_01.fsa 及对应的检测数值
- **特色**：支持水平滚动，移动端友好

### 检测图谱
- **显示范围**：横轴 0-7000，纵轴 0-4000
- **图表类型**：蓝色波峰曲线
- **交互**：支持缩放和查看详细数据点

### 风险评估结果
- **评估项目**：肝脏健康、食管癌风险、胃癌风险、胰癌风险、结直肠癌、血液肿瘤风险、免疫年龄评估
- **颜色标识**：
  - 🟢 低风险：绿色背景
  - 🟡 中风险：黄色背景
  - 🔴 高风险：红色背景

### 审核操作
- ✅ **通过审核**：绿色按钮
- ❌ **驳回审核**：红色按钮
- 📝 **添加备注**：蓝色按钮
- 📊 **生成报告**：灰色按钮

### 底部信息
- **推荐人**：万海波
- **客户信息**：左凌 男 43岁
- **诊断**：可编辑输入框

## 🚀 快速启动

### 方法一：快速预览（推荐）
1. 双击 `mobile-test.html` 文件
2. 在浏览器中直接查看完整界面

### 方法二：Python服务器
1. 双击 `simple-start.bat`
2. 访问 http://localhost:8000/mobile-test.html

### 方法三：Next.js完整版
1. 双击 `start.bat`
2. 访问 http://localhost:3000

## 📱 移动端测试

### 开发者工具测试
1. 按 F12 打开开发者工具
2. 点击设备切换图标 📱
3. 选择不同设备尺寸测试：
   - iPhone SE (375x667)
   - iPhone 12 Pro (390x844)
   - Samsung Galaxy S20 Ultra (412x915)
   - iPad Air (820x1180)

### 测试要点
- ✅ 顶部标题在小屏幕正确换行
- ✅ 数据表格可水平滑动
- ✅ 风险评估颜色标识清晰
- ✅ 审核按钮易于点击
- ✅ 文字大小清晰可读

## 🛠️ 技术架构

- **前端框架**：Next.js 14 + TypeScript
- **样式系统**：Tailwind CSS
- **移动端优化**：响应式设计 + 触摸友好
- **图表组件**：HTML5 Canvas 绘制
- **兼容性**：支持现代浏览器和移动设备

## 📋 文件结构

```
康鑫达医疗报告审核系统/
├── app/                          # Next.js App Router
│   ├── page.tsx                 # 主页面
│   ├── layout.tsx              # 布局组件
│   └── globals.css             # 全局样式
├── components/                  # React组件
│   ├── MedicalHeader.tsx       # 医疗报告头部
│   ├── MedicalDataTable.tsx    # 数据表格
│   ├── MedicalChart.tsx        # 检测图谱
│   ├── RiskAssessmentPanel.tsx # 风险评估
│   └── MedicalFooter.tsx       # 底部信息
├── mobile-test.html            # 移动端测试页面
├── start.bat                   # Next.js启动脚本
├── simple-start.bat           # Python服务器启动脚本
├── TESTING.md                 # 测试指南
└── package.json               # 项目配置
```

## 🔧 自定义配置

### 修改医疗数据
编辑 `app/page.tsx` 文件中的数据：

```typescript
const tableData = [
  {
    no: "您的样本编号",
    p1: 数值1,
    p2: 数值2,
    // ... 其他P值
    result: "计算结果"
  }
];

const riskAssessment = {
  sampleId: "样本ID",
  liverHealth: { value: 32, risk: "低风险" },
  // ... 其他风险评估
};
```

### 修改患者信息
```typescript
const patientInfo = {
  recommender: "推荐人姓名",
  patientName: "患者姓名",
  gender: "性别",
  age: 年龄,
  diagnosis: "诊断信息"
};
```

## 🎯 使用场景

1. **医疗机构**：日常检测报告审核
2. **研究机构**：实验数据分析和管理
3. **移动办公**：随时随地进行报告审核
4. **质量控制**：检测结果的标准化管理

## 📞 技术支持

如需技术支持或功能定制，请提供：
1. 具体需求描述
2. 使用环境信息
3. 相关截图或日志
4. 联系方式

---

**注意事项：**
- 建议使用现代浏览器（Chrome、Safari、Firefox、Edge）
- 移动端测试时保持网络连接稳定
- 数据仅为演示用途，实际使用请替换为真实数据
- 系统支持自定义样式和功能扩展

**版本信息：**
- 当前版本：v1.0.0
- 更新日期：2025-08-24
- 兼容性：支持iOS 13+、Android 8+
