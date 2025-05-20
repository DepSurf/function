# Function: <code>get_mm_exe_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107d9f0)
Location: kernel/fork.c:758
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_exe_link
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8107d9f0-ffffffff8107da4e: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f590)
Location: kernel/fork.c:793
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:do_coredump
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8107f590-ffffffff8107f5ee: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81083c40)
Location: kernel/fork.c:947
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:do_coredump
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81083c40-ffffffff81083c9e: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080b10)
Location: kernel/fork.c:994
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:do_coredump
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81080b10-ffffffff81080b5b: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810873b0)
Location: kernel/fork.c:1006
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:do_coredump
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810873b0-ffffffff81087401: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b817)
Location: kernel/fork.c:1075
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:get_task_exe_file
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:do_coredump
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8108ad60-ffffffff8108adb1: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810922f0)
Location: kernel/fork.c:1131
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:do_coredump
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810922f0-ffffffff81092341: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096640)
Location: kernel/fork.c:1148
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81096640-ffffffff8109667a: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109cc00)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8109cc00-ffffffff8109cc3a: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3840)
Location: kernel/fork.c:1177
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_multicast
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810a3840-ffffffff810a3877: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f1f0)
Location: kernel/fork.c:1174
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_multicast
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8109f1f0-ffffffff8109f23d: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a00c0)
Location: kernel/fork.c:1180
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_multicast
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810a00c0-ffffffff810a010d: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3220)
Location: kernel/fork.c:1261
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/audit.c:audit_log_multicast
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810b3220-ffffffff810b326d: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9420)
Location: kernel/fork.c:1333
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810c9420-ffffffff810c9481: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6940)
Location: kernel/fork.c:1357
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810e6940-ffffffff810e69a1: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f22e0)
Location: kernel/fork.c:1498
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810f22e0-ffffffff810f2341: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc1e5)
Location: kernel/fork.c:1494
Inline: True
Inline callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
Direct callers:
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit_watch.c:audit_exe_compare
  - fs/coredump.c:cn_print_exe_file
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810fc160-ffffffff810fc195: get_mm_exe_file (STB_GLOBAL)
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
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1848)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffff8000100f1848-ffff8000100f18bc: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350c0c)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - fs/coredump.c:format_corename
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
c0350c0c-c0350c74: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000136610)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
c000000000136610-c000000000136668: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000beeea)
Location: kernel/fork.c:1163
Inline: True
Inline callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffe0000be322-ffffffe0000be374: get_mm_exe_file (STB_GLOBAL)
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
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096520)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81096520-ffffffff8109655a: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084fa0)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff81084fa0-ffffffff81084fda: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810964d0)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff810964d0-ffffffff8109650a: get_mm_exe_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *get_mm_exe_file(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e490)
Location: kernel/fork.c:1163
Inline: False
Direct callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/audit.c:audit_log_d_path_exe
  - security/tomoyo/util.c:tomoyo_get_exe
```
**Symbols:**

```
ffffffff8109e490-ffffffff8109e4e5: get_mm_exe_file (STB_GLOBAL)
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
