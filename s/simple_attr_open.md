# Function: <code>simple_attr_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234330)
Location: fs/libfs.c:758
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - drivers/cpufreq/intel_pstate.c:fops_pid_param_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open
```
**Symbols:**

```
ffffffff81234330-ffffffff812343ce: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125c8b0)
Location: fs/libfs.c:786
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/cpufreq/intel_pstate.c:fops_pid_param_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
```
**Symbols:**

```
ffffffff8125c8b0-ffffffff8125c94e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126fe00)
Location: fs/libfs.c:794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/cpufreq/intel_pstate.c:fops_pid_param_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
```
**Symbols:**

```
ffffffff8126fe00-ffffffff8126fe9e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d5e0)
Location: fs/libfs.c:795
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/cpufreq/intel_pstate.c:fops_pid_param_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:count_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
  - drivers/ras/cec.c:pfn_ops_open
```
**Symbols:**

```
ffffffff8127d5e0-ffffffff8127d67e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a0080)
Location: fs/libfs.c:795
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:count_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
  - drivers/ras/cec.c:pfn_ops_open
```
**Symbols:**

```
ffffffff812a0080-ffffffff812a011e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6830)
Location: fs/libfs.c:795
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:count_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
  - drivers/ras/cec.c:pfn_ops_open
```
**Symbols:**

```
ffffffff812c6830-ffffffff812c68ce: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dba30)
Location: fs/libfs.c:795
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:count_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
  - drivers/ras/cec.c:pfn_ops_open
```
**Symbols:**

```
ffffffff812dba30-ffffffff812dbace: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa0c0)
Location: fs/libfs.c:814
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff812fa0c0-ffffffff812fa15e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130bde0)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff8130bde0-ffffffff8130be7e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345870)
Location: fs/libfs.c:888
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff81345870-ffffffff8134590e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351c40)
Location: fs/libfs.c:890
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff81351c40-ffffffff81351cde: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358960)
Location: fs/libfs.c:893
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff81358960-ffffffff813589fe: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6fa0)
Location: fs/libfs.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff813a6fa0-ffffffff813a703e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142bd30)
Location: fs/libfs.c:929
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff8142bd30-ffffffff8142bddd: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8f00)
Location: fs/libfs.c:930
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - kernel/dma/swiotlb.c:fops_io_tlb_used_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/clk/clk-fractional-divider.c:clk_fd_denominator_fops_open
  - drivers/clk/clk-fractional-divider.c:clk_fd_numerator_fops_open
  - drivers/mmc/core/debugfs.c:mmc_err_state_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff814b8f00-ffffffff814b8fad: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ee1e0)
Location: fs/libfs.c:925
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - kernel/dma/swiotlb.c:fops_io_tlb_hiwater_open
  - kernel/dma/swiotlb.c:fops_io_tlb_used_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/clk/clk-fractional-divider.c:clk_fd_denominator_fops_open
  - drivers/clk/clk-fractional-divider.c:clk_fd_numerator_fops_open
  - drivers/mmc/core/debugfs.c:mmc_err_state_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff814ee1e0-ffffffff814ee28d: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521f50)
Location: fs/libfs.c:1195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - kernel/dma/swiotlb.c:fops_io_tlb_hiwater_open
  - kernel/dma/swiotlb.c:fops_io_tlb_used_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/clk.c:clk_phase_fops_open
  - drivers/clk/clk.c:clk_rate_fops_open
  - drivers/clk/clk-fractional-divider.c:clk_fd_denominator_fops_open
  - drivers/clk/clk-fractional-divider.c:clk_fd_numerator_fops_open
  - drivers/mmc/core/debugfs.c:mmc_caps2_fops_open
  - drivers/mmc/core/debugfs.c:mmc_caps_fops_open
  - drivers/mmc/core/debugfs.c:mmc_err_state_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff81521f50-ffffffff8152202c: simple_attr_open (STB_GLOBAL)
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
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c0430)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:vcpu_stat_fops_open
  - virt/kvm/kvm_main.c:vm_stat_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_fops_open
```
**Symbols:**

```
ffff8000103c0430-ffff8000103c04cc: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d868)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - arch/arm/mach-omap2/pm-debug.c:pm_dbg_option_fops_open
  - arch/arm/mach-omap2/pm-debug.c:pwrdm_suspend_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/clk/tegra/clk-dfll.c:rate_fops_open
  - drivers/clk/tegra/clk-dfll.c:lock_fops_open
  - drivers/clk/tegra/clk-dfll.c:enable_fops_open
  - drivers/power/avs/smartreflex.c:pm_sr_fops_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_fops_open
  - drivers/memory/tegra/tegra124-emc.c:emc_debug_rate_fops_open
```
**Symbols:**

```
c059d868-c059d8f8: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004c0370)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup_64.c:fops_rfi_flush_open
  - arch/powerpc/kernel/security.c:fops_count_cache_flush_open
  - arch/powerpc/kernel/security.c:fops_stf_barrier_open
  - arch/powerpc/kernel/security.c:fops_barrier_nospec_open
  - arch/powerpc/kernel/eeh.c:eeh_enable_dbgfs_ops_open
  - arch/powerpc/mm/book3s64/hash_utils.c:fops_hpt_order_open
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_diag_data_fops_open
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_ops_inbB_open
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_ops_inbA_open
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_dbgfs_ops_outb_open
  - arch/powerpc/platforms/powernv/opal-imc.c:fops_imc_x64_open
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_fops_open
  - arch/powerpc/xmon/xmon.c:xmon_dbgfs_ops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
```
**Symbols:**

```
c0000000004c0370-c0000000004c0450: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000280bf4)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_fops_open
```
**Symbols:**

```
ffffffe000280bf4-ffffffe000280c90: simple_attr_open (STB_GLOBAL)
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
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813043c0)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff813043c0-ffffffff8130445e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f4fe0)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff812f4fe0-ffffffff812f507e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813021b0)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff813021b0-ffffffff8130224e: simple_attr_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int simple_attr_open(struct inode *inode, struct file *file, int (*get)(void *, u64 *), int (*set)(void *, u64), const char *fmt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813137d0)
Location: fs/libfs.c:852
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_fops_open
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mcr_fops_open
  - kernel/panic.c:clear_warn_once_fops_open
  - mm/memory.c:fault_around_bytes_fops_open
  - mm/huge_memory.c:split_huge_pages_fops_open
  - fs/debugfs/file.c:fops_atomic_t_wo_open
  - fs/debugfs/file.c:fops_atomic_t_ro_open
  - fs/debugfs/file.c:fops_atomic_t_open
  - fs/debugfs/file.c:fops_size_t_wo_open
  - fs/debugfs/file.c:fops_size_t_ro_open
  - fs/debugfs/file.c:fops_size_t_open
  - fs/debugfs/file.c:fops_x64_wo_open
  - fs/debugfs/file.c:fops_x64_ro_open
  - fs/debugfs/file.c:fops_x64_open
  - fs/debugfs/file.c:fops_x32_wo_open
  - fs/debugfs/file.c:fops_x32_ro_open
  - fs/debugfs/file.c:fops_x32_open
  - fs/debugfs/file.c:fops_x16_wo_open
  - fs/debugfs/file.c:fops_x16_ro_open
  - fs/debugfs/file.c:fops_x16_open
  - fs/debugfs/file.c:fops_x8_wo_open
  - fs/debugfs/file.c:fops_x8_ro_open
  - fs/debugfs/file.c:fops_x8_open
  - fs/debugfs/file.c:fops_ulong_wo_open
  - fs/debugfs/file.c:fops_ulong_ro_open
  - fs/debugfs/file.c:fops_ulong_open
  - fs/debugfs/file.c:fops_u64_wo_open
  - fs/debugfs/file.c:fops_u64_ro_open
  - fs/debugfs/file.c:fops_u64_open
  - fs/debugfs/file.c:fops_u32_wo_open
  - fs/debugfs/file.c:fops_u32_ro_open
  - fs/debugfs/file.c:fops_u32_open
  - fs/debugfs/file.c:fops_u16_wo_open
  - fs/debugfs/file.c:fops_u16_ro_open
  - fs/debugfs/file.c:fops_u16_open
  - fs/debugfs/file.c:fops_u8_wo_open
  - fs/debugfs/file.c:fops_u8_ro_open
  - fs/debugfs/file.c:fops_u8_open
  - drivers/mmc/core/debugfs.c:mmc_clock_fops_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_dev_state_open
  - drivers/ras/cec.c:action_threshold_ops_open
  - drivers/ras/cec.c:decay_interval_ops_open
```
**Symbols:**

```
ffffffff813137d0-ffffffff8131386e: simple_attr_open (STB_GLOBAL)
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
