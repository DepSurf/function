# Function: <code>proc_pident_readdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127df00)
Location: fs/proc/base.c:2313
Inline: False
Direct callers:
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
```
**Symbols:**

```
ffffffff8127df00-ffffffff8127e089: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812aaf30)
Location: fs/proc/base.c:2404
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
```
**Symbols:**

```
ffffffff812aaf30-ffffffff812ab0aa: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812c0e30)
Location: fs/proc/base.c:2439
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
```
**Symbols:**

```
ffffffff812c0e30-ffffffff812c0fa9: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ce150)
Location: fs/proc/base.c:2471
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
  - fs/proc/base.c:proc_selinux_attr_dir_iterate
```
**Symbols:**

```
ffffffff812ce150-ffffffff812ce2d1: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f29b0)
Location: fs/proc/base.c:2472
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
  - fs/proc/base.c:proc_selinux_attr_dir_iterate
```
**Symbols:**

```
ffffffff812f29b0-ffffffff812f2b38: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131f840)
Location: fs/proc/base.c:2470
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
```
**Symbols:**

```
ffffffff8131f840-ffffffff8131f9b7: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81336960)
Location: fs/proc/base.c:2490
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff81336960-ffffffff81336ad7: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135ea20)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff8135ea20-ffffffff8135ebad: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81376c80)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff81376c80-ffffffff81376e0d: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bfac0)
Location: fs/proc/base.c:2637
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff813bfac0-ffffffff813bfc7a: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d1950)
Location: fs/proc/base.c:2651
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff813d1950-ffffffff813d1b0a: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d8840)
Location: fs/proc/base.c:2650
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff813d8840-ffffffff813d89fa: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81429f70)
Location: fs/proc/base.c:2656
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff81429f70-ffffffff8142a12a: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a3420)
Location: fs/proc/base.c:2685
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff814a3420-ffffffff814a35d3: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815386b0)
Location: fs/proc/base.c:2689
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff815386b0-ffffffff81538863: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815708f0)
Location: fs/proc/base.c:2689
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff815708f0-ffffffff81570aac: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a9290)
Location: fs/proc/base.c:2683
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff815a9290-ffffffff815a944c: proc_pident_readdir (STB_LOCAL)
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
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800010442320)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffff800010442320-ffff80001044251c: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0607b40)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
c0607b40-c0607d30: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0000000005579f0)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
c0000000005579f0-c000000000557ca4: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d8f9c)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffe0002d8f9c-ffffffe0002d9134: proc_pident_readdir (STB_LOCAL)
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
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136f260)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff8136f260-ffffffff8136f3ed: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135fcf0)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff8135fcf0-ffffffff8135fe7d: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136cd30)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff8136cd30-ffffffff8136cebd: proc_pident_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_pident_readdir(struct file *file, struct dir_context *ctx, const struct pid_entry *ents, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81380640)
Location: fs/proc/base.c:2504
Inline: False
Direct callers:
  - fs/proc/base.c:proc_tid_base_readdir
  - fs/proc/base.c:proc_tgid_base_readdir
  - fs/proc/base.c:proc_attr_dir_readdir
  - fs/proc/base.c:proc_apparmor_attr_dir_iterate
  - fs/proc/base.c:proc_smack_attr_dir_iterate
```
**Symbols:**

```
ffffffff81380640-ffffffff813807d3: proc_pident_readdir (STB_LOCAL)
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
