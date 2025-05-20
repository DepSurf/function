# Function: <code>sysfs_unmerge_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8128d270)
Location: fs/sysfs/group.c:311
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff8128d270-ffffffff8128d2c7: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812ba8f0)
Location: fs/sysfs/group.c:311
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff812ba8f0-ffffffff812ba947: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812d0020)
Location: fs/sysfs/group.c:311
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff812d0020-ffffffff812d0077: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff812dd6f0)
Location: fs/sysfs/group.c:311
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff812dd6f0-ffffffff812dd747: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81302020)
Location: fs/sysfs/group.c:311
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff81302020-ffffffff81302077: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8132fff0)
Location: fs/sysfs/group.c:320
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff8132fff0-ffffffff81330047: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81347390)
Location: fs/sysfs/group.c:335
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff81347390-ffffffff813473e7: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8136f790)
Location: fs/sysfs/group.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff8136f790-ffffffff8136f7e7: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81387af0)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff81387af0-ffffffff81387b47: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813d2cd0)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff813d2cd0-ffffffff813d2d27: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813e4a30)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff813e4a30-ffffffff813e4a87: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813eb630)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff813eb630-ffffffff813eb687: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8143d3c0)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff8143d3c0-ffffffff8143d417: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff814b8d00)
Location: fs/sysfs/group.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff814b8d00-ffffffff814b8d63: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815503d0)
Location: fs/sysfs/group.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff815503d0-ffffffff81550433: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815880c0)
Location: fs/sysfs/group.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff815880c0-ffffffff81588123: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff815c0c80)
Location: fs/sysfs/group.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff815c0c80-ffffffff815c0ce3: sysfs_unmerge_group (STB_GLOBAL)
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
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffff800010457c48)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffff800010457c48-ffff800010457cb4: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c0619edc)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
c0619edc-c0619f44: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (c0000000005721e0)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
c0000000005721e0-c000000000572284: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffe0002e8ef8)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffe0002e8ef8-ffffffe0002e8f56: sysfs_unmerge_group (STB_GLOBAL)
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
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813800d0)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff813800d0-ffffffff81380127: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff81370b60)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff81370b60-ffffffff81370bb7: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff8137dba0)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff8137dba0-ffffffff8137dbf7: sysfs_unmerge_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sysfs_unmerge_group(struct kobject *kobj, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/group.c (ffffffff813916a0)
Location: fs/sysfs/group.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_remove
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_latency_tolerance
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_flags
  - drivers/base/power/sysfs.c:pm_qos_sysfs_remove_resume_latency
  - drivers/base/power/sysfs.c:wakeup_sysfs_remove
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
  - drivers/usb/core/sysfs.c:usb_remove_sysfs_dev_files
```
**Symbols:**

```
ffffffff813916a0-ffffffff813916f7: sysfs_unmerge_group (STB_GLOBAL)
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
