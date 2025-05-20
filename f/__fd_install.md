# Function: <code>__fd_install</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a8c0)
Location: fs/file.c:603
Inline: True
Direct callers:
  - fs/file.c:SyS_dup
  - fs/file.c:f_dupfd
```
**Symbols:**

```
ffffffff8122a8c0-ffffffff8122a99f: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81253020)
Location: fs/file.c:604
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
```
**Symbols:**

```
ffffffff81253020-ffffffff812530ff: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81266280)
Location: fs/file.c:604
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
```
**Symbols:**

```
ffffffff81266280-ffffffff8126634b: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273a60)
Location: fs/file.c:590
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
```
**Symbols:**

```
ffffffff81273a60-ffffffff81273b25: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296390)
Location: fs/file.c:591
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup
```
**Symbols:**

```
ffffffff81296390-ffffffff81296410: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc7f0)
Location: fs/file.c:586
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff812bc7f0-ffffffff812bc870: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1ab0)
Location: fs/file.c:586
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff812d1ab0-ffffffff812d1b30: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eeac0)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff812eeac0-ffffffff812eeb4a: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300580)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff81300580-ffffffff8130060a: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339730)
Location: fs/file.c:592
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff81339730-ffffffff813397ba: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b2248)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffff8000103b2248-ffff8000103b2320: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591660)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
c0591660-c0591710: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae090)
Location: fs/file.c:587
Inline: False
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
c0000000004ae090-c0000000004ae184: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002762fc)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffe0002762fc-ffffffe0002763b8: __fd_install (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8b60)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff812f8b60-ffffffff812f8bea: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9780)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff812e9780-ffffffff812e980a: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6970)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff812f6970-ffffffff812f69fa: __fd_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __fd_install(struct files_struct *files, unsigned int fd, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307ba0)
Location: fs/file.c:587
Inline: True
Direct callers:
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
```
**Symbols:**

```
ffffffff81307ba0-ffffffff81307c50: __fd_install (STB_GLOBAL)
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
