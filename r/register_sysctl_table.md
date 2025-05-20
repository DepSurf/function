# Function: <code>register_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81286310)
Location: fs/proc/proc_sysctl.c:1502
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/core.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81286310-ffffffff81286331: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b34b0)
Location: fs/proc/proc_sysctl.c:1508
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff812b34b0-ffffffff812b34d1: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c8d00)
Location: fs/proc/proc_sysctl.c:1514
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff812c8d00-ffffffff812c8d21: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d6070)
Location: fs/proc/proc_sysctl.c:1578
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff812d6070-ffffffff812d6091: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812fa8b0)
Location: fs/proc/proc_sysctl.c:1579
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff812fa8b0-ffffffff812fa8d1: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81327a60)
Location: fs/proc/proc_sysctl.c:1581
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81327a60-ffffffff81327a81: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133ebf0)
Location: fs/proc/proc_sysctl.c:1580
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff8133ebf0-ffffffff8133ec11: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81366f20)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81366f20-ffffffff81366f41: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137f1b0)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff8137f1b0-ffffffff8137f1d1: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c9240)
Location: fs/proc/proc_sysctl.c:1588
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff813c9240-ffffffff813c9261: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813db230)
Location: fs/proc/proc_sysctl.c:1588
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff813db230-ffffffff813db251: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e2160)
Location: fs/proc/proc_sysctl.c:1592
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff813e2160-ffffffff813e2181: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81433c70)
Location: fs/proc/proc_sysctl.c:1592
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81433c70-ffffffff81433c91: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814adc59)
Location: fs/proc/proc_sysctl.c:1652
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_base
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814adc20-ffffffff814adc4b: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81544189)
Location: fs/proc/proc_sysctl.c:1651
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_base
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81544140-ffffffff8154416b: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044c770)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffff80001044c770-ffff80001044c7b0: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c06111d4)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/arm/kernel/isa.c:register_isa_ports
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
c06111d4-c0611204: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000564030)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/powerpc/kernel/idle.c:register_powersave_nap_sysctl
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
c000000000564030-c000000000564058: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e17f2)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffe0002e17f2-ffffffe0002e182c: register_sysctl_table (STB_GLOBAL)
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
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81377790)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81377790-ffffffff813777b1: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81368260)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
**Symbols:**

```
ffffffff81368260-ffffffff81368281: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375260)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81375260-ffffffff81375281: register_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ctl_table_header *register_sysctl_table(struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81388c30)
Location: fs/proc/proc_sysctl.c:1605
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/sysctl.c:sysctl_init
  - kernel/sched/debug.c:register_sched_domain_sysctl
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/quota/dquot.c:dquot_init
  - fs/devpts/inode.c:init_devpts_fs
  - ipc/ipc_sysctl.c:ipc_sysctl_init
  - ipc/mq_sysctl.c:mq_register_sysctl_table
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_ldisc.c:tty_sysctl_init
  - drivers/char/hpet.c:hpet_init
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81388c30-ffffffff81388c51: register_sysctl_table (STB_GLOBAL)
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
