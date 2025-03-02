# Retirement_calculator  
职工延迟退休年龄计算器

## 简介
这是一个用于计算职工延迟退休年龄的工具，适用于不同类型的人员（正常退休/特殊工种/领取病残津贴人员）。该工具提供图形界面，方便用户输入出生年月和人员类型，自动计算延迟退休日期、弹性退休范围、最低缴费年限等信息。

## 下载与安装
1. 点击[此处](https://github.com/wayzlin/Retirement_calculator//releases)下载最新的 `retirement_calculator.exe` 文件。
2. 下载完成后，双击运行 `retirement_calculator.exe`，无需额外安装。

**注意**：此工具仅在 Windows 10 系统上测试过，其他Windows版本不保证正常运行，其他操作系统（如 Mac 或 Linux）无法运行。

## 使用说明
1. **选择人员类型**：
   - 在界面上选择适合的人员类型，例如：
     - 1 - 男职工（原法定退休年龄：60周岁）
     - 2 - 女职工（原法定退休年龄：55周岁）
     - 3 - 女工人（原法定退休年龄：50周岁）
     - 4 - 特殊工种男职工（原法定退休年龄：55周岁）
     - 5 - 特殊工种女工人（原法定退休年龄：45周岁）
     - 6-8 - 病残津贴相关选项
2.  **输入出生年月**：
   - 在“出生年月”栏中输入6位数字的年月，格式为` YYYYMM `，例如` 197001 `表示1970年1月。
3.  **点击“计算”或按Enter 键**：
   - 系统将自动计算并显示：
     - 延迟后法定退休年月
     - 弹性最早和最晚退休年月
     - 退休年龄
     - 最低缴费年限
4.  **其他功能**：
   -  **选择具体退休日期（Alt+Q）**：手动输入退休日期，查看该日期下的详细信息（仅适用于正常退休和特殊工种）。
   -  **不足最低缴费年限（Alt+W）**：计算在缴费不足的情况下，还需缴纳多久才能满足退休条件（仅适用于正常退休）。
   -  **必须阅读免责声明（Alt+E）**：查看免责声明，了解使用注意事项。

## 示例  
- **输入**：
   -  人员类型：1 - 男职工  
   -  出生年月：197001  
- **输出**：
   - 延迟后现退休年月：2031年05月  
   - 延迟月数：16个月  
   - 退休年龄：61周岁4个月  
   - 最低缴费年限：16年
   - 
   - 弹性最早退休年月：2030年01月  
   - 延迟月数：0个月  
   - 退休年龄：60周岁  
   - 最低缴费年限：15.5年
   - 
   - 弹性最晚退休年月：2034年05月  
   - 延迟月数：52个月  
   - 退休年龄：64周岁4个月  
   - 最低缴费年限：16年  

## 免责声明  
1. 本计算器仅供参考，不排除计算或显示有误。具体退休政策及执行标准请以国家和地方最新政策为准。  
2. 计算结果不构成任何法律依据，使用者应以当地人力资源和社会保障局以及社会保险事业中心的正式官方通知为准。  
3. 本软件开发者不对因使用本计算器而产生的任何后果承担责任。

## 反馈  
如有问题或建议，请在GitHub 仓库提交[ Issue ] ( [https://github.com/wayzlin/Retirement_calculator/issues )或联系开发者。
