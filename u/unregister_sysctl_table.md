# Function: <code>unregister_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81284920)
Location: fs/proc/proc_sysctl.c:1567
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff81284920-ffffffff812849a1: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b19f0)
Location: fs/proc/proc_sysctl.c:1573
Inline: False
Direct callers:
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff812b19f0-ffffffff812b1a71: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c7290)
Location: fs/proc/proc_sysctl.c:1579
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff812c7290-ffffffff812c7311: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d4620)
Location: fs/proc/proc_sysctl.c:1643
Inline: True
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff812d4620-ffffffff812d46c9: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f8e50)
Location: fs/proc/proc_sysctl.c:1644
Inline: True
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff812f8e50-ffffffff812f8ef9: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81326740)
Location: fs/proc/proc_sysctl.c:1646
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff81326740-ffffffff813267cc: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133da30)
Location: fs/proc/proc_sysctl.c:1646
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff8133da30-ffffffff8133dabc: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81365910)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff81365910-ffffffff8136599c: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137dba0)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff8137dba0-ffffffff8137dc2c: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c91df)
Location: fs/proc/proc_sysctl.c:1656
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff813c8340-ffffffff813c83d9: unregister_sysctl_table.part.0 (STB_LOCAL)
ffffffff813c83e0-ffffffff813c8406: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813db1cf)
Location: fs/proc/proc_sysctl.c:1656
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff813da330-ffffffff813da3c9: unregister_sysctl_table.part.0 (STB_LOCAL)
ffffffff813da3d0-ffffffff813da3f6: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e20ff)
Location: fs/proc/proc_sysctl.c:1660
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff813e1180-ffffffff813e1219: unregister_sysctl_table.part.0 (STB_LOCAL)
ffffffff813e1220-ffffffff813e1246: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81433c0f)
Location: fs/proc/proc_sysctl.c:1660
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff81432c30-ffffffff81432cc9: unregister_sysctl_table.part.0 (STB_LOCAL)
ffffffff81432cd0-ffffffff81432cf6: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814adba6)
Location: fs/proc/proc_sysctl.c:1729
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - drivers/char/hpet.c:hpet_init
  - drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/scsi/sg.c:exit_sg
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff814abfb0-ffffffff814ac058: unregister_sysctl_table.part.0 (STB_LOCAL)
ffffffff814ac060-ffffffff814ac08d: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815440a6)
Location: fs/proc/proc_sysctl.c:1728
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - drivers/char/hpet.c:hpet_init
  - drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/scsi/sg.c:exit_sg
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff815427a0-ffffffff81542848: unregister_sysctl_table.part.0 (STB_LOCAL)
ffffffff81542860-ffffffff8154288d: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157a910)
Location: fs/proc/proc_sysctl.c:1519
Inline: True
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - drivers/char/hpet.c:hpet_init
  - drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/scsi/sg.c:exit_sg
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - drivers/hv/hv_common.c:hv_common_free
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff8157a910-ffffffff8157a955: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b31f0)
Location: fs/proc/proc_sysctl.c:1515
Inline: True
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - drivers/char/hpet.c:hpet_init
  - drivers/base/firmware_loader/fallback_table.c:unregister_firmware_config_sysctl
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/scsi/sg.c:exit_sg
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - drivers/hv/hv_common.c:hv_common_free
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff815b31f0-ffffffff815b3235: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044ad30)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffff80001044ad30-ffff80001044ae18: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060fb74)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
c060fb74-c060fc24: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000561610)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
c000000000561610-c000000000561740: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e040e)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffe0002e040e-ffffffe0002e0506: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81376180)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff81376180-ffffffff8137620c: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81366c50)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff81366c50-ffffffff81366cdc: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81373c50)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff81373c50-ffffffff81373cdc: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813871f0)
Location: fs/proc/proc_sysctl.c:1673
Inline: False
Direct callers:
  - arch/x86/kernel/itmt.c:sched_clear_itmt_support
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/sched/debug.c:unregister_sched_domain_sysctl
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_exit_sysctl
  - drivers/cdrom/cdrom.c:cdrom_exit
  - drivers/md/md.c:md_exit
  - net/sysctl_net.c:unregister_net_sysctl_table
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff813871f0-ffffffff81387275: unregister_sysctl_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
