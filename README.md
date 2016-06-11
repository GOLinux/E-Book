# <center>说&nbsp;&nbsp;明
--------
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RAID 的意思是廉价磁盘冗余阵列（Redundant Array of Inexpensive Disks），但现在它被称为独立磁盘冗余阵列（Redundant Array of Independent Drives）。早先一个容量很小的磁盘都是非常昂贵的，但是现在我们可以很便宜的买到一个更大的磁盘。Raid 是一系列放在一起，成为一个逻辑卷的磁盘集合。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这个系列被命名为“在 Linux 下使用 RAID”，分为9个部分，包括以下主题：
- 第1部分：介绍 RAID 的级别和概念
- 第2部分：在Linux中如何设置 RAID0（条带化）
- 第3部分：在Linux中如何设置 RAID1（镜像化）
- 第4部分：在Linux中如何设置 RAID5（条带化与分布式奇偶校验）
- 第5部分：在Linux中如何设置 RAID6（条带双分布式奇偶校验）
- 第6部分：在Linux中设置 RAID 10 或1 + 0（嵌套）
- 第7部分：增加现有的 RAID 阵列并删除损坏的磁盘
- 第8部分：在 RAID 中恢复（重建）损坏的驱动器
- 第9部分：在 Linux 中管理 RAID

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这是9篇系列教程的第1部分，在这里我们将介绍 RAID 的概念和 RAID 级别，这是在 Linux 中构建 RAID 需要理解的。
