# Function: <code>kernel_read_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812394a0)
Location: fs/exec.c:886
Inline: True
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812394a0-ffffffff812396ab: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124c1e0)
Location: fs/exec.c:891
Inline: True
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff8124c1e0-ffffffff8124c3eb: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812582f0)
Location: fs/exec.c:917
Inline: True
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812582f0-ffffffff812584f0: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127a690)
Location: fs/exec.c:900
Inline: True
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff8127a690-ffffffff8127a860: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a1200)
Location: fs/exec.c:904
Inline: True
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812a1200-ffffffff812a139d: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b6480)
Location: fs/exec.c:907
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812b6480-ffffffff812b6637: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d31f0)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812d31f0-ffffffff812d3398: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4d80)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812e4d80-ffffffff812e4f28: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff8131be20)
Location: fs/exec.c:933
Inline: True
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path_initns
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff8131be20-ffffffff8131bf78: kernel_read_file.part.0 (STB_LOCAL)
ffffffff8131bf80-ffffffff8131bfd1: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81365b00)
Location: fs/kernel_read_file.c:35
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/kernel_read_file.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff81365b00-ffffffff81365d86: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8136c540)
Location: fs/kernel_read_file.c:35
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/kernel_read_file.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff8136c540-ffffffff8136c7c6: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff813bb210)
Location: fs/kernel_read_file.c:35
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/kernel_read_file.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff813bb210-ffffffff813bb496: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81441170)
Location: fs/kernel_read_file.c:35
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/kernel_read_file.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff81441170-ffffffff81441457: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernel_read_file(struct file *file, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff814d00b0)
Location: fs/kernel_read_file.c:35
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file_from_fd
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/kernel_read_file.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff814d00b0-ffffffff814d03d0: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernel_read_file(struct file *file, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81506350)
Location: fs/kernel_read_file.c:35
Inline: False
Direct callers:
  - kernel/module/main.c:init_module_from_file
  - fs/kernel_read_file.c:kernel_read_file_from_fd
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/kernel_read_file.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff81506350-ffffffff8150667f: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernel_read_file(struct file *file, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8153b070)
Location: fs/kernel_read_file.c:35
Inline: False
Direct callers:
  - kernel/module/main.c:init_module_from_file
  - fs/kernel_read_file.c:kernel_read_file_from_fd
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/kernel_read_file.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff8153b070-ffffffff8153b39f: kernel_read_file (STB_GLOBAL)
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
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038c7e0)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffff80001038c7e0-ffff80001038c9e4: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0574398)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
c0574398-c057462c: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000484710)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
c000000000484710-c0000000004849fc: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025de42)
Location: fs/exec.c:908
Inline: True
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffe00025de42-ffffffe00025dfa2: kernel_read_file (STB_GLOBAL)
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
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dd360)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812dd360-ffffffff812dd508: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cdfe0)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812cdfe0-ffffffff812ce188: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812db170)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812db170-ffffffff812db318: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_read_file(struct file *file, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ec0f0)
Location: fs/exec.c:908
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_fd
  - fs/exec.c:kernel_read_file_from_path
```
**Symbols:**

```
ffffffff812ec0f0-ffffffff812ec298: kernel_read_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t buf_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t *file_size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t *size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t max_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, buf, size, max_size, id</code> ➡️ <code>file, offset, buf, buf_size, file_size, id</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
