# Function: <code>wait_for_space</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81279970)
Location: fs/splice.c:1091
Inline: True
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff81279970-ffffffff81279a0a: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81286ed0)
Location: fs/splice.c:1087
Inline: True
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff81286ed0-ffffffff81286f6d: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a96c0)
Location: fs/splice.c:1071
Inline: True
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff812a96c0-ffffffff812a975c: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d0420)
Location: fs/splice.c:1072
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812d0420-ffffffff812d04be: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e5640)
Location: fs/splice.c:1076
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812e5640-ffffffff812e56de: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81303e50)
Location: fs/splice.c:1073
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81303e50-ffffffff81303ee3: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81316ed0)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81316ed0-ffffffff81316f63: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813503c0)
Location: fs/splice.c:1069
Inline: False
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff813503c0-ffffffff8135044e: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135d5e0)
Location: fs/splice.c:986
Inline: True
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8135d5e0-ffffffff8135d67b: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81364080)
Location: fs/splice.c:987
Inline: True
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
```
**Symbols:**

```
ffffffff81364080-ffffffff8136411b: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b2870)
Location: fs/splice.c:989
Inline: True
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
```
**Symbols:**

```
ffffffff813b2870-ffffffff813b290b: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814378f0)
Location: fs/splice.c:985
Inline: True
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
```
**Symbols:**

```
ffffffff814378f0-ffffffff814379b3: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c5a30)
Location: fs/splice.c:984
Inline: True
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
```
**Symbols:**

```
ffffffff814c5a30-ffffffff814c5af3: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fb0c0)
Location: fs/splice.c:1205
Inline: True
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
```
**Symbols:**

```
ffffffff814fb0c0-ffffffff814fb16a: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8152fdc0)
Location: fs/splice.c:1264
Inline: True
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
```
**Symbols:**

```
ffffffff8152fdc0-ffffffff8152fe6a: wait_for_space (STB_LOCAL)
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
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cd8e8)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffff8000103cd8e8-ffff8000103cd9bc: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a94a4)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
```
**Symbols:**

```
c05a94a4-c05a9570: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004cf970)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
c0000000004cf970-c0000000004cfac4: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028ab8a)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffe00028ab8a-ffffffe00028ac24: wait_for_space (STB_LOCAL)
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
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130f4b0)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8130f4b0-ffffffff8130f543: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813000c0)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff813000c0-ffffffff81300153: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130d2a0)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8130d2a0-ffffffff8130d333: wait_for_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int wait_for_space(struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131ea90)
Location: fs/splice.c:1074
Inline: True
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8131ea90-ffffffff8131eb23: wait_for_space (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
