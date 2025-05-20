# Function: <code>mm_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107e3e0)
Location: kernel/fork.c:797
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_auxv
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff8107e3e0-ffffffff8107e474: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810800e0)
Location: kernel/fork.c:855
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_auxv
```
**Symbols:**

```
ffffffff810800e0-ffffffff81080178: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084a40)
Location: kernel/fork.c:1009
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff81084a40-ffffffff81084ad8: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081920)
Location: kernel/fork.c:1056
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff81081920-ffffffff810819b8: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810881f0)
Location: kernel/fork.c:1068
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810881f0-ffffffff81088288: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108bf40)
Location: kernel/fork.c:1137
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff8108bf40-ffffffff8108bfd6: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093800)
Location: kernel/fork.c:1193
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff81093800-ffffffff81093896: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097f00)
Location: kernel/fork.c:1210
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff81097f00-ffffffff81097f95: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e5c0)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff8109e5c0-ffffffff8109e655: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5c90)
Location: kernel/fork.c:1239
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810a5c90-ffffffff810a5d25: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1670)
Location: kernel/fork.c:1236
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810a1670-ffffffff810a1705: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a23f0)
Location: kernel/fork.c:1242
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810a23f0-ffffffff810a2485: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3af0)
Location: kernel/fork.c:1321
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810b3af0-ffffffff810b3b85: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9d50)
Location: kernel/fork.c:1393
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810c9d50-ffffffff810c9e29: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e7370)
Location: kernel/fork.c:1417
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810e7370-ffffffff810e7460: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2e80)
Location: kernel/fork.c:1558
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810f2e80-ffffffff810f2f76: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc230)
Location: kernel/fork.c:1554
Inline: False
Direct callers:
  - mm/madvise.c:__do_sys_process_madvise
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff810fc230-ffffffff810fc326: mm_access (STB_GLOBAL)
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
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3418)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffff8000100f3418-ffff8000100f34c0: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03518c4)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
c03518c4-c035195c: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138ec0)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
c000000000138ec0-c000000000138fa4: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0ff2)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffe0000c0ff2-ffffffe0000c1176: mm_access (STB_GLOBAL)
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
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097ee0)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff81097ee0-ffffffff81097f75: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086940)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff81086940-ffffffff810869d5: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097e90)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff81097e90-ffffffff81097f25: mm_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mm_struct *mm_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fa90)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
**Symbols:**

```
ffffffff8109fa90-ffffffff8109fb25: mm_access (STB_GLOBAL)
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
