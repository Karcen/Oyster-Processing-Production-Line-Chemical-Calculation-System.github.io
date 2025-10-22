# Oyster Processing Production Line Chemical Calculation System

牡蛎加工生产线化工计算系统

---

## Table of Contents / 目录

- [Project Overview / 项目概述](#project-overview--项目概述)
- [System Features / 系统功能](#system-features--系统功能)
- [Technical Characterisåtics / 技术特点](#technical-characteristics--技术特点)
- [Calculation Methods / 计算方法](#calculation-methods--计算方法)
- [System Architecture / 系统架构](#system-architecture--系统架构)
- [Usage Guide / 使用指南](#usage-guide--使用指南)
- [Deployment Instructions / 部署说明](#deployment-instructions--部署说明)
- [License / 许可证](#license--许可证)

---

## Project Overview / 项目概述

### English
The Oyster Processing Production Line Chemical Calculation System is a professional engineering calculation tool designed for the design and optimization of oyster processing production lines with an annual output of 200,000 tons. The system is built based on chemical engineering principles and provides comprehensive material balance and energy balance calculations.

### 中文
牡蛎加工生产线化工计算系统是一个专业的工程计算工具，专为年产20万吨牡蛎加工生产线的设计和优化而开发。该系统基于化工原理构建，提供全面的物料衡算和能量衡算计算。

---

## System Features / 系统功能

### English
- **Complete Process Calculation**: Covers 11 process units from raw material pretreatment to final product drying
- **Rigorous Chemical Engineering Calculations**: Based on standard chemical engineering principles and equations
- **Material Balance Analysis**: Comprehensive material balance verification with visualization charts
- **Energy Balance Calculation**: Detailed energy consumption analysis using thermodynamic principles
- **Equipment Sizing**: Precise equipment selection and sizing calculations
- **Technical Economic Analysis**: Investment estimation and economic benefit evaluation
- **Interactive Interface**: User-friendly web interface with visualization tools

### 中文
- **完整工艺计算**：涵盖从原料预处理到最终产品干燥的11个工艺单元
- **严谨化工计算**：基于标准化工原理和方程
- **物料衡算分析**：全面的物料平衡验证，配有可视化图表
- **能量衡算计算**：基于热力学原理的详细能耗分析
- **设备选型计算**：精确的设备选择和尺寸计算
- **技术经济分析**：投资估算和经济效益评估
- **交互式界面**：用户友好的网页界面，配有可视化工具

---

## Technical Characteristics / 技术特点

### English
- **Modern Web Technology**: Built with HTML5, CSS3, JavaScript
- **Responsive Design**: Compatible with different screen sizes
- **Mathematical Formula Display**: Uses MathJax for professional formula rendering
- **Data Visualization**: Integrates Chart.js for interactive charts
- **Professional UI**: Uses Tailwind CSS for modern and clean interface
- **Chemical Engineering Equations**: Implements standard chemical engineering formulas

### 中文
- **现代网页技术**：使用HTML5、CSS3、JavaScript构建
- **响应式设计**：适配不同屏幕尺寸
- **数学公式显示**：使用MathJax进行专业公式渲染
- **数据可视化**：集成Chart.js实现交互式图表
- **专业界面设计**：使用Tailwind CSS实现现代简洁的界面
- **化工方程实现**：采用标准化工计算公式

---

## Calculation Methods / 计算方法

### English

#### Material Balance Calculation
Based on the law of conservation of mass:
\[ \text{Input} = \text{Output} + \text{Accumulation} \]

#### Energy Balance Calculation
Based on the first law of thermodynamics:
\[ \Delta H + \Delta E_k + \Delta E_p = Q + W \]

#### Filtration Calculation
Constant pressure filtration equation:
\[ V^2 + 2VV_e = KA^2t \]
\[ K = \frac{2\Delta P}{\mu(r'c)} \]

#### Evaporation Calculation
\[ W = G_{\text{feed}} \times \left(1 - \frac{w_1}{w_2}\right) \]

#### Pump Power Calculation
\[ P = \frac{Q \times H \times \rho \times g}{3600 \times 1000 \times \eta} \]

### 中文

#### 物料衡算
基于质量守恒定律：
\[ \text{输入} = \text{输出} + \text{积累} \]

#### 能量衡算
基于热力学第一定律：
\[ \Delta H + \Delta E_k + \Delta E_p = Q + W \]

#### 过滤计算
恒压过滤方程：
\[ V^2 + 2VV_e = KA^2t \]
\[ K = \frac{2\Delta P}{\mu(r'c)} \]

#### 蒸发计算
\[ W = G_{\text{进料}} \times \left(1 - \frac{w_1}{w_2}\right) \]

#### 泵功率计算
\[ P = \frac{Q \times H \times \rho \times g}{3600 \times 1000 \times \eta} \]

---

## System Architecture / 系统架构

### English

#### Main Process Units
1. **Raw Material Pretreatment**
   - Raw material loading calculation
   - Washing tank calculation
   - Near-infrared sorting machine calculation

2. **Shelling Processing**
   - Bucket elevator calculation
   - Manual shelling calculation

3. **Wet Processing**
   - Continuous homogenizer calculation
   - Enzymatic hydrolysis tank calculation

4. **Separation and Purification**
   - Plate and frame filter calculation
   - Membrane filtration calculation

5. **Concentration and Drying**
   - Double-effect evaporator calculation
   - Spray drying calculation

### 中文

#### 主要工艺单元
1. **原料预处理单元**
   - 原料装车计算
   - 清洗池计算
   - 近红外挑选机计算

2. **剥壳处理单元**
   - 斗式提升机计算
   - 人工剥壳计算

3. **湿法加工单元**
   - 连续匀浆机计算
   - 酶解罐计算

4. **分离纯化单元**
   - 板框过滤机计算
   - 膜过滤机计算

5. **浓缩干燥单元**
   - 双效蒸发器计算
   - 喷雾干燥计算

---

## Usage Guide / 使用指南

### English

#### Basic Operation
1. **Access the System**: Open the HTML file in a modern web browser
2. **View Process Flow**: Browse the complete process flow diagram
3. **Select Calculation Unit**: Click on any equipment node to view detailed calculations
4. **View Calculation Steps**: Each calculation includes assumptions, formulas, and numerical substitution
5. **Check Results**: Review calculation results and verification

#### Key Features
- **Interactive Flowchart**: Click equipment nodes to view calculations
- **Detailed Calculations**: Each step includes complete calculation process
- **Visualization**: View material balance charts and energy consumption data
- **Economic Analysis**: Check investment estimation and economic benefits

### 中文

#### 基本操作
1. **访问系统**：在现代网页浏览器中打开HTML文件
2. **查看工艺流程**：浏览完整的工艺流程示意图
3. **选择计算单元**：点击任何设备节点查看详细计算
4. **查看计算步骤**：每个计算包含假设条件、公式和数值代入
5. **检查结果**：查看计算结果和验证

#### 主要功能
- **交互式流程图**：点击设备节点查看计算
- **详细计算过程**：每一步都包含完整的计算过程
- **可视化展示**：查看物料平衡图表和能耗数据
- **经济分析**：查看投资估算和经济效益

---

## Deployment Instructions / 部署说明

### English

#### Local Deployment
1. **Download Files**: Save the HTML file to your local machine
2. **Open in Browser**: Double-click the HTML file to open in a web browser
3. **No Additional Setup**: No server or database required for local use

#### Web Deployment
1. **Upload to Server**: Upload the HTML file to your web server
2. **Configure Hosting**: Set up proper MIME types if needed
3. **Access via URL**: Users can access via the web URL
4. **Mobile Compatibility**: The system is responsive and works on mobile devices

### 中文

#### 本地部署
1. **下载文件**：将HTML文件保存到本地计算机
2. **浏览器打开**：双击HTML文件在网页浏览器中打开
3. **无需额外设置**：本地使用无需服务器或数据库

#### 网页部署
1. **上传到服务器**：将HTML文件上传到网页服务器
2. **配置托管**：根据需要设置MIME类型
3. **通过URL访问**：用户可以通过网页URL访问
4. **移动设备兼容**：系统响应式设计，支持移动设备

---

## License / 许可证

### English
This project is licensed under the MIT License - see the LICENSE file for details.

### 中文
本项目采用MIT许可证 - 详见LICENSE文件。

---


*This README file provides a comprehensive guide to the Oyster Processing Production Line Chemical Calculation System. For any questions or issues, please contact the development team.*

*本README文件提供了牡蛎加工生产线化工计算系统的全面指南。如有任何问题或问题，请联系karcenzheng@yeah.net。*
