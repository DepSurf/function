# Function: <code>fuse_send_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81315680)
Location: fs/fuse/file.c:23
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff81315680-ffffffff81315729: fuse_send_open.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81349ed0)
Location: fs/fuse/file.c:23
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff81349ed0-ffffffff81349f79: fuse_send_open.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8135f810)
Location: fs/fuse/file.c:23
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff8135f810-ffffffff8135f8b9: fuse_send_open.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813742f0)
Location: fs/fuse/file.c:23
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff813742f0-ffffffff81374398: fuse_send_open.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81399070)
Location: fs/fuse/file.c:23
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff81399070-ffffffff81399118: fuse_send_open.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813c7dc0)
Location: fs/fuse/file.c:23
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff813c7dc0-ffffffff813c7e66: fuse_send_open.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff813e1010)
Location: fs/fuse/file.c:24
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff813e1010-ffffffff813e10b6: fuse_send_open.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8140cc10)
Location: fs/fuse/file.c:22
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff8140cc10-ffffffff8140ccb6: fuse_send_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81426730)
Location: fs/fuse/file.c:34
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff81426730-ffffffff814267cd: fuse_send_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_conn *fc, u64 nodeid, struct file *file, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81475770)
Location: fs/fuse/file.c:35
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff81475770-ffffffff8147580e: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_mount *fm, u64 nodeid, struct file *file, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81490400)
Location: fs/fuse/file.c:35
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff81490400-ffffffff8149050b: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81495e30)
Location: fs/fuse/file.c:22
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_open
  - fs/fuse/file.c:fuse_file_open
```
**Symbols:**

```
ffffffff81495e30-ffffffff81495f39: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ed8f0)
Location: fs/fuse/file.c:22
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_open
  - fs/fuse/file.c:fuse_file_open
```
**Symbols:**

```
ffffffff814ed8f0-ffffffff814ed9f9: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157c840)
Location: fs/fuse/file.c:22
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_open
  - fs/fuse/file.c:fuse_file_open
```
**Symbols:**

```
ffffffff8157c840-ffffffff8157c959: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81622350)
Location: fs/fuse/file.c:22
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_open
  - fs/fuse/file.c:fuse_file_open
```
**Symbols:**

```
ffffffff81622350-ffffffff81622469: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165a7a0)
Location: fs/fuse/file.c:23
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_open
  - fs/fuse/file.c:fuse_file_open
```
**Symbols:**

```
ffffffff8165a7a0-ffffffff8165a8bb: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_mount *fm, u64 nodeid, unsigned int open_flags, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81694470)
Location: fs/fuse/file.c:24
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_open
  - fs/fuse/file.c:fuse_file_open
```
**Symbols:**

```
ffffffff81694470-ffffffff8169458b: fuse_send_open (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffff80001050a308)
Location: fs/fuse/file.c:34
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffff80001050a308-ffff80001050a3d8: fuse_send_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c8314)
Location: fs/fuse/file.c:34
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_conn *fc, u64 nodeid, struct file *file, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c00000000064fa90)
Location: fs/fuse/file.c:34
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
c00000000064fa90-c00000000064fba0: fuse_send_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_send_open(struct fuse_conn *fc, u64 nodeid, struct file *file, int opcode, struct fuse_open_out *outargp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000375534)
Location: fs/fuse/file.c:34
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffe000375534-ffffffe0003755ec: fuse_send_open (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8141ed10)
Location: fs/fuse/file.c:34
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff8141ed10-ffffffff8141edad: fuse_send_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8140f790)
Location: fs/fuse/file.c:34
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff8140f790-ffffffff8140f82d: fuse_send_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8141aeb0)
Location: fs/fuse/file.c:34
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff8141aeb0-ffffffff8141af4d: fuse_send_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff814320a0)
Location: fs/fuse/file.c:34
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_do_open
  - fs/fuse/file.c:fuse_do_open
```
**Symbols:**

```
ffffffff814320a0-ffffffff8143213d: fuse_send_open.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_mount *fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn *fc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int open_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file</code>
</li>
</ul>
</details>
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
</ul>
