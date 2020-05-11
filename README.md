# 《知识建模与知识管理》课程相关资料  
项目包含2020年知识建模与知识管理课程的阅读资料、课件、课程计划，以及前几年学生的课程作业、演示系统、参考项目、技术资料等。  同学们也可以在这里讨论技术问题。  各分支的内容如下。  
**必读清单**：学生作业说明与实例。  
**课件与课程安排**：课件PPT、教学计划等。  
**经典文献阅读和近年文献**：知识建模与知识管理的经典文献，以及近年在该领域重要期刊会议上的论文（近年文献可选作为课程报告的阅读文献，但注意同学之间不能有重合的）。  
**本体建模、编程工具与技术资料**：本体建模、编程语言与实现技术的相关参考资料。  
**前人作业集锦**：前几年学生的课程作业、已发表的知识建模与知识管理案例文献，可作为课程大作业的参考（案例文献亦可选作为课程报告的阅读文献，但注意同学之间不能有重合的）。  
**相关著名项目参考**：知识建模与知识管理案例项目。  
**姚莉课题组本体演示系统**：为解决空间目标识别的问题，课题组基于构建的空间目标识别本体，开发的空间目标识别系统演示文档。  


**附：下载单个文件夹或者文件的方法**（整个项目的文件可在网页直接下载，这里以下载 *课件与课程安排* 分支为例）  
安装git程序（不会的话自行百度）。  
创建一个文件夹存放要下载的文件（这里以*devops*为例）。  
在命令行中输入以下命令。  
cd devops  
git init  
git remote add -f origin https://github.com/liubin0314/Knowledge-Modeling-and-Knowledge-Management.git  
git config core.sparsecheckout true  
git pull origin 课件与课程安排分支  
