# Function: <code>dup_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a2c0)
Location: fs/file.c:289
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8122a2c0-ffffffff8122a52c: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252a10)
Location: fs/file.c:290
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
```
**Symbols:**

```
ffffffff81252a10-ffffffff81252c7a: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265c70)
Location: fs/file.c:290
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
```
**Symbols:**

```
ffffffff81265c70-ffffffff81265ee2: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273450)
Location: fs/file.c:276
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
```
**Symbols:**

```
ffffffff81273450-ffffffff812736c1: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295d80)
Location: fs/file.c:277
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
```
**Symbols:**

```
ffffffff81295d80-ffffffff81295ff1: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc250)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
```
**Symbols:**

```
ffffffff812bc250-ffffffff812bc4bc: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1510)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
```
**Symbols:**

```
ffffffff812d1510-ffffffff812d177c: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ee530)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff812ee530-ffffffff812ee777: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ffff0)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff812ffff0-ffffffff81300237: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339120)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81339120-ffffffff813393a8: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, unsigned int max_fds, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344d90)
Location: fs/file.c:287
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81344d90-ffffffff8134504a: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, unsigned int max_fds, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b120)
Location: fs/file.c:287
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8134b120-ffffffff8134b3ce: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, unsigned int max_fds, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398f80)
Location: fs/file.c:287
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81398f80-ffffffff8139922e: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, unsigned int max_fds, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141b890)
Location: fs/file.c:316
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8141b890-ffffffff8141bb65: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, unsigned int max_fds, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a79d0)
Location: fs/file.c:316
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814a79d0-ffffffff814a7ca5: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, unsigned int max_fds, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dc9b0)
Location: fs/file.c:316
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814dc9b0-ffffffff814dcc85: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, unsigned int max_fds, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150f170)
Location: fs/file.c:316
Inline: False
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8150f170-ffffffff8150f445: dup_fd (STB_GLOBAL)
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
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b19a8)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff8000103b19a8-ffff8000103b1cfc: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590f60)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0590f60-c0591244: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ad5f0)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0000000004ad5f0-c0000000004ad9ec: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000275bfe)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe000275bfe-ffffffe000275eda: dup_fd (STB_GLOBAL)
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
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f85d0)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff812f85d0-ffffffff812f8817: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e91f0)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff812e91f0-ffffffff812e9437: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f63e0)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff812f63e0-ffffffff812f6627: dup_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct files_struct *dup_fd(struct files_struct *oldf, int *errorp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813075f0)
Location: fs/file.c:272
Inline: False
Direct callers:
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff813075f0-ffffffff8130784e: dup_fd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int max_fds</code>
</li>
<li>
<b>Param reordered. </b>
<code>oldf, errorp</code> ➡️ <code>oldf, max_fds, errorp</code>
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
