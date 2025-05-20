# Function: <code>do_dup2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229f40)
Location: fs/file.c:817
Inline: False
Direct callers:
  - fs/file.c:replace_fd
  - fs/file.c:SyS_dup2
```
**Symbols:**

```
ffffffff81229f40-ffffffff8122a016: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812526b0)
Location: fs/file.c:823
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812526b0-ffffffff8125276c: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265920)
Location: fs/file.c:823
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81265920-ffffffff812659d7: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273060)
Location: fs/file.c:809
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81273060-ffffffff81273117: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295990)
Location: fs/file.c:812
Inline: False
Direct callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81295990-ffffffff81295a47: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bbc20)
Location: fs/file.c:808
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812bbc20-ffffffff812bbcd7: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d0ea0)
Location: fs/file.c:838
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812d0ea0-ffffffff812d0f57: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eded0)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812eded0-ffffffff812edf83: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ff990)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812ff990-ffffffff812ffa43: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338aa0)
Location: fs/file.c:869
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81338aa0-ffffffff81338b59: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344520)
Location: fs/file.c:1005
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81344520-ffffffff813445d9: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134a8c0)
Location: fs/file.c:1017
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff8134a8c0-ffffffff8134a979: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398670)
Location: fs/file.c:1077
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81398670-ffffffff81398729: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141adc0)
Location: fs/file.c:1079
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff8141adc0-ffffffff8141ae91: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a6fc0)
Location: fs/file.c:1089
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff814a6fc0-ffffffff814a7093: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dbfa0)
Location: fs/file.c:1104
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff814dbfa0-ffffffff814dc07d: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150e1c0)
Location: fs/file.c:1233
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff8150e1c0-ffffffff8150e29d: do_dup2 (STB_LOCAL)
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
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b0f48)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffff8000103b0f48-ffff8000103b10a0: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590a38)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
c0590a38-c0590b90: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004acbe0)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
c0000000004acbe0-c0000000004acddc: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000275484)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffe000275484-ffffffe00027561a: do_dup2 (STB_LOCAL)
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
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f7f70)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812f7f70-ffffffff812f8023: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8b90)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812e8b90-ffffffff812e8c43: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5d80)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff812f5d80-ffffffff812f5e33: do_dup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_dup2(struct files_struct *files, struct file *file, unsigned int fd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81306ea0)
Location: fs/file.c:844
Inline: False
Direct callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
**Symbols:**

```
ffffffff81306ea0-ffffffff81306f5d: do_dup2 (STB_LOCAL)
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
