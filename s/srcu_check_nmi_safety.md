# Function: <code>srcu_check_nmi_safety</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In kernel/notifier.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In security/tomoyo/mount.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/srcu.h:121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In kernel/notifier.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/mount.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In kernel/notifier.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In fs/tracefs/event_inode.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/file.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/mount.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/network.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/securityfs_if.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/gpu/drm/drm_drv.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/srcu.h:151
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
