RFC中为指明要求级别所使用的关键词
========================================================

# 文档状态

本文档为互联网社区指定了"**互联网当前最佳实践（Internet Best Current Practices）**，以及与之相关的改进意见。本文档对发行方式无限制。

# 摘要

在很多标准跟踪文档（standards track documents）中，使用了一些关键词用来标明要求级别，并使用大写字符来书写。本文档定义了这些关键词在IETF文档中的含义。文档撰写者在开始撰写文档之前，请参考本文档中对这些关键词的相关说明。

关键词列表如下：

    MUST             
    MUST NOT         
    REQUIRED         
    SHALL            
    SHALL NOT        
    SHOULD           
    SHOULD NOT       
    RECOMMENDED      
    NOT RECOMMENDED  
    MAY              
    OPTIONAL         

使用响应关键词时，请注意相关语境。

# 关键词说明

## MUST

"**MUST**" "**REQUIRED**" 和"**SHALL**"这三个关键词的含义相同，表示"**必须遵守**"。

## MUST NOT

"**MUST NOT**"和"**SHALL NOT**"具有相同的含义，表示"**绝对禁止**"。

## SHOULD

"**SHOULD**"和"**RECOMMENDED**"表示，在特殊情况下，可以忽略规范所定义某项条目，但在使用的时候，应当完全清楚相关后果。

## SHOULD NOT

"**SHOULD NOT**"和"**NOT RECOMMENDED**"表示，在特殊情况下，某项条目时可以接受或有用的，但在使用的时候，应当完全清楚相关后果。

## MAY

"**MAY**"和"**OPTIONAL**"表示，某项条目是可选的。生产厂商可以根据自身需要，自行选择是否实现该条目。若某项具体实现中没有包含某个可选条目，则其 **必须（MUST）**可以同另一个实现了该可选条目的实现正常协作，不过可以在与之相关的功能上酌情削减。同样的，包含了某个可选条目的实现，也 **必须（MUST）**可以与另一个未包含该条目的实现正常协作。

# 关键词使用说明
本文档中所定义的关键词必须小心使用，只有当必须要使用，或者为了限制可能的意外情况时才使用。例如，不应该在必须要的地方对实现者强加限制。

# 安全考虑

使用本文档中所列举的关键词时，往往包含了对安全性方面的考虑。在安全性方面，"没有实现 **MUST**或 **SHOULD**"和"做了 **MUST NOT**或 **SHOULD NOT**"是有细微区别的。文档作者应该充分考虑使用关键词时可能带来的问题，以免实现者对其中可能存在的问题做无谓的探讨。

# 鸣谢

本文档中所定义的关键词是从各个RFC文档中摘取出来的，此外，与使用相关的建议则离不开大家的帮助，尤其是Robert Ullmann，Thomas Narten，Neal McBurnett和Robert Elz。

# 作者地址

   Scott Bradner
   Harvard University
   1350 Mass. Ave.
   Cambridge, MA 02138
   phone - +1 617 495 3864
   email - sob@harvard.edu