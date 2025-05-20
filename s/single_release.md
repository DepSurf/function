# Function: <code>single_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230e20)
Location: fs/seq_file.c:602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - drivers/rtc/rtc-proc.c:rtc_proc_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff81230e20-ffffffff81230e56: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259130)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - drivers/rtc/rtc-proc.c:rtc_proc_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff81259130-ffffffff81259166: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c5e0)
Location: fs/seq_file.c:612
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - drivers/rtc/rtc-proc.c:rtc_proc_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff8126c5e0-ffffffff8126c616: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a1a0)
Location: fs/seq_file.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/rtc/rtc-proc.c:rtc_proc_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff8127a1a0-ffffffff8127a1d6: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129cc20)
Location: fs/seq_file.c:602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/rtc/rtc-proc.c:rtc_proc_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff8129cc20-ffffffff8129cc56: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c2f50)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff812c2f50-ffffffff812c2f8d: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d7ec0)
Location: fs/seq_file.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff812d7ec0-ffffffff812d7efd: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f63c0)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff812f63c0-ffffffff812f6401: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81307f90)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff81307f90-ffffffff81307fd1: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341d20)
Location: fs/seq_file.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff81341d20-ffffffff81341d61: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e3e0)
Location: fs/seq_file.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff8134e3e0-ffffffff8134e421: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81354670)
Location: fs/seq_file.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff81354670-ffffffff813546b1: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2a50)
Location: fs/seq_file.c:627
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff813a2a50-ffffffff813a2a91: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814267a0)
Location: fs/seq_file.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff814267a0-ffffffff814267e5: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b3000)
Location: fs/seq_file.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff814b3000-ffffffff814b3045: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e8050)
Location: fs/seq_file.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff814e8050-ffffffff814e8095: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151bee0)
Location: fs/seq_file.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/build_utility.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_file_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff8151bee0-ffffffff8151bf25: single_release (STB_GLOBAL)
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
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bbaf8)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffff8000103bbaf8-ffff8000103bbb48: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c059927c)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
  - sound/core/info.c:snd_info_text_entry_release
```
**Symbols:**

```
c059927c-c05992c4: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b8f90)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
c0000000004b8f90-c0000000004b9004: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d572)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffe00027d572-ffffffe00027d5c4: single_release (STB_GLOBAL)
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
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300570)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff81300570-ffffffff813005b1: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f1190)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff812f1190-ffffffff812f11d1: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe360)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff812fe360-ffffffff812fe3a1: single_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int single_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f6a0)
Location: fs/seq_file.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - kernel/sched/psi.c:psi_fop_release
  - kernel/trace/trace.c:tracing_single_release_tr
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/proc_net.c:single_release_net
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_release
  - block/blk-mq-debugfs.c:blk_mq_debugfs_release
  - drivers/ras/debugfs.c:trace_release
```
**Symbols:**

```
ffffffff8130f6a0-ffffffff8130f6e1: single_release (STB_GLOBAL)
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
