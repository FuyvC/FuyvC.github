执行总结

1.引言

  自2018年5月10日开始的一周时间内，小组确定了以“私人医生系统”为主题的项目开发计划，旨在为用户提供更为便捷高效的网上医疗服务。开发成员分工合作，初步分析并确定了用户需求；对整个项目的开发背景及项目概况有了基本的认识；合作完成项目建议书；并初步明确了开发环境和开发语言，确定了后端逻辑设计和基于数据库的数据存取技术，确定了前端网页页面的设计概要及相应技术。
  
2.项目概述

  “私人医生系统”目的是为各个家庭提供专属的医疗服务。注册过信息的用户可以根据医生的地理位置和所属科室在网上自主选择心仪的医生。医生根据用户的症状在网上给出医嘱。“私人医生系统”使得医生与患者之间能够使用网络渠道充分交流沟通，为用户病情的解决以及日常保健提供保证。
  
3.团队成员

  项目小组由10人组成。每位成员均为本科大三在读学生，主修方向为软件工程web工程方向。
  
4.目标市场的描述和预测

  忙于工作或忙于家务的人群，往往缺乏时间或是不愿意花费大量的时间前往医院看病治疗。对此，“私人医生系统”提供了一种很好的线上医疗平台使得医生能够在线诊治病情。此外，目前医疗服务行业存在挂号难，排队久，专家需要提前很长时间预约等问题。对于想尽快明确病情的患者，“私人医生系统”无疑是一种很好的选择。
  “私人医生系统”具有使用方便，用户足不出户的特点，相信在医疗市场具有较强的市场竞争力。
  
5.总结

  一周时间内，项目小组已经对“私人医生系统”项目确定了初步的开发计划。这主要得益于项目成员的开发热情和组内成员相对明确的分工合作。但是仍然存在需要解决的问题。例如，“私人医生系统”需要大量具有丰富诊治经验的专业医生。这些医生往往需要花费大量的时间去寻找，现今“私人医生系统”的在线医生数量还有所不足。此外，对于预算和投放市场的收益还需要更为准确的判定。需求是否满足用户标准也需要在今后的开发过程中进行判断和调整。希望在日后的开发过程中，小组成员能够加强沟通联系，开发出切实可行，令人满意的成品。
  
  ------------------------------------------------------------------------------------------------------------------------------
  
  7其他需求

7.1易用性需求

“私人医生系统”的设计和实现遵循易用性原则，用户的界面布局清晰易懂，操作步骤简单明了，会使用基本Windows操作的非专业人员都可以可熟练使用此系统。

（1）使用方便，设计合理。

（2）使用“私人医生系统”的过程中有必要的操作提示信息。

（3）用户要完成浏览医生资料，查看推荐医生，预约医生，查看医嘱等操作，只需要注册登陆后依据提示信息点击相应按钮即可，无需复杂操作。


7.2安全性需求

为了对软件的安装和使用进行统一的管理，“私人医生系统”需要得到管理人员的授权才能使用。软件采用注册-允许登录的方式达到这一要求。启动并使用软件时，应对软件的授权信息进行检查，缺少授权信息情况软件将自动关闭。为了防止偶然或恶意的访问、使用、修改或泄密，实施以下两方面的安全措施。

1.资料安全和用户权限管理

所有资料（业务资料和工作资料）统一管理，不同用户具备不同权限，不同权限的用户访问不同的资料，对敏感资料只有经过授权才能访问，并且对非特权用户只能只读访问，特权用户才能修改其中的内容。 对于资料的防灾难恢复，采取数据库备份的方法，将数据库备份在不同的计算机上，这一操作由系统管理员来完成。同时，还应该从制度上作规定，要求管理员严格按照备份周期来备份，并严格控制操作员的工作，将所有的信息记录下来，内容包括：操作员姓名、备份日期、备份内容、备份文件所在的位置等信息。

2.完善的日志管理

所有的数据库操作都有操作日志，包括打开某个数据库、进行的所有操作都记录在案已备参阅。在出现问题时能从日志中分析出非法操作和破坏性操作，能够从日志中追查责任。
  
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/FuyvC/FuyvC.github/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/FuyvC/FuyvC.github/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
