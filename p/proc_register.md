# Function: <code>proc_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f210)
Location: fs/proc/generic.c:336
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
```
**Symbols:**

```
ffffffff8127f210-ffffffff8127f317: proc_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac250)
Location: fs/proc/generic.c:340
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812ac250-ffffffff812ac358: proc_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1b40)
Location: fs/proc/generic.c:340
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812c1b40-ffffffff812c1c48: proc_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ceb30)
Location: fs/proc/generic.c:323
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812ceb30-ffffffff812cec48: proc_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3310)
Location: fs/proc/generic.c:325
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812f3310-ffffffff812f3447: proc_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320610)
Location: fs/proc/generic.c:350
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81320610-ffffffff81320740: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337700)
Location: fs/proc/generic.c:350
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81337700-ffffffff81337836: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f840)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff8135f840-ffffffff8135f9b6: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377aa0)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81377aa0-ffffffff81377c16: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0950)
Location: fs/proc/generic.c:362
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813c0950-ffffffff813c0a45: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d27a0)
Location: fs/proc/generic.c:372
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813d27a0-ffffffff813d2895: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d95a0)
Location: fs/proc/generic.c:367
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813d95a0-ffffffff813d9763: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142acd0)
Location: fs/proc/generic.c:367
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff8142acd0-ffffffff8142ae93: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4320)
Location: fs/proc/generic.c:367
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff814a4320-ffffffff814a44f0: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539780)
Location: fs/proc/generic.c:367
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81539780-ffffffff81539950: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571a00)
Location: fs/proc/generic.c:366
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81571a00-ffffffff81571bb1: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa3b0)
Location: fs/proc/generic.c:366
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff815aa3b0-ffffffff815aa561: proc_register (STB_GLOBAL)
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
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443860)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffff800010443860-ffff800010443a10: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608adc)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
c0608adc-c0608c54: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000558f10)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
c000000000558f10-c000000000559108: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da3e2)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffe0002da3e2-ffffffe0002da526: proc_register (STB_GLOBAL)
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
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370080)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81370080-ffffffff813701f6: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360b10)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81360b10-ffffffff81360c86: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136db50)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff8136db50-ffffffff8136dcc6: proc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_register(struct proc_dir_entry *dir, struct proc_dir_entry *dp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381480)
Location: fs/proc/generic.c:351
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81381480-ffffffff81381600: proc_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct proc_dir_entry *</code>
</li>
</ul>
</details>
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
