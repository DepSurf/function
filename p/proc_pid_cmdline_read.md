# Function: <code>proc_pid_cmdline_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t _count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127cda0)
Location: fs/proc/base.c:199
Inline: False
```
**Symbols:**

```
ffffffff8127cda0-ffffffff8127d2d0: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t _count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812aa020)
Location: fs/proc/base.c:199
Inline: False
```
**Symbols:**

```
ffffffff812aa020-ffffffff812aa52d: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t _count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bf940)
Location: fs/proc/base.c:202
Inline: False
```
**Symbols:**

```
ffffffff812bf940-ffffffff812bfe4d: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t _count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cc440)
Location: fs/proc/base.c:211
Inline: False
```
**Symbols:**

```
ffffffff812cc440-ffffffff812cc90c: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t _count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f0bc0)
Location: fs/proc/base.c:212
Inline: False
```
**Symbols:**

```
ffffffff812f0bc0-ffffffff812f108c: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131e250)
Location: fs/proc/base.c:333
Inline: True
```
**Symbols:**

```
ffffffff8131e250-ffffffff8131e58c: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81334e10)
Location: fs/proc/base.c:337
Inline: True
```
**Symbols:**

```
ffffffff81334e10-ffffffff8133514c: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8135bd5a)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffffffff8135bad0-ffffffff8135becd: proc_pid_cmdline_read (STB_LOCAL)
ffffffff8135f0ca-ffffffff8135f0d6: proc_pid_cmdline_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813741aa)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffffffff81373f20-ffffffff81374330: proc_pid_cmdline_read (STB_LOCAL)
ffffffff8137732a-ffffffff81377336: proc_pid_cmdline_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bd1c0)
Location: fs/proc/base.c:357
Inline: False
```
**Symbols:**

```
ffffffff813bd1c0-ffffffff813bd286: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813cee10)
Location: fs/proc/base.c:357
Inline: False
```
**Symbols:**

```
ffffffff813cee10-ffffffff813ceed6: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d66a0)
Location: fs/proc/base.c:356
Inline: False
```
**Symbols:**

```
ffffffff813d66a0-ffffffff813d6766: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81427f70)
Location: fs/proc/base.c:358
Inline: False
```
**Symbols:**

```
ffffffff81427f70-ffffffff81428036: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a0020)
Location: fs/proc/base.c:357
Inline: False
```
**Symbols:**

```
ffffffff814a0020-ffffffff814a00f4: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81534f00)
Location: fs/proc/base.c:358
Inline: False
```
**Symbols:**

```
ffffffff81534f00-ffffffff81534fd4: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156d0c0)
Location: fs/proc/base.c:359
Inline: False
```
**Symbols:**

```
ffffffff8156d0c0-ffffffff8156d197: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a5a10)
Location: fs/proc/base.c:359
Inline: False
```
**Symbols:**

```
ffffffff815a5a10-ffffffff815a5ae7: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043fbe0)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffff80001043fbe0-ffff800010440060: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0604a80)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
c0604a80-c0604efc: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000553c10)
Location: fs/proc/base.c:355
Inline: False
```
**Symbols:**

```
c000000000553c10-c00000000055412c: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d6e62)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffffffe0002d6e62-ffffffe0002d7108: proc_pid_cmdline_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8136c78a)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffffffff8136c500-ffffffff8136c910: proc_pid_cmdline_read (STB_LOCAL)
ffffffff8136f90a-ffffffff8136f916: proc_pid_cmdline_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8135d21a)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffffffff8135cf90-ffffffff8135d3a0: proc_pid_cmdline_read (STB_LOCAL)
ffffffff8136039a-ffffffff813603a6: proc_pid_cmdline_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8136a25a)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffffffff81369fd0-ffffffff8136a3e0: proc_pid_cmdline_read (STB_LOCAL)
ffffffff8136d3da-ffffffff8136d3e6: proc_pid_cmdline_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t proc_pid_cmdline_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8137db25)
Location: fs/proc/base.c:355
Inline: True
```
**Symbols:**

```
ffffffff8137d8a0-ffffffff8137dc9a: proc_pid_cmdline_read (STB_LOCAL)
ffffffff81380d00-ffffffff81380d0c: proc_pid_cmdline_read.cold (STB_LOCAL)
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
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t _count</code>
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
