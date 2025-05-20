# Function: <code>get_pipe_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81216050)
Location: fs/pipe.c:1080
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:vmsplice_to_user
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
```
**Symbols:**

```
ffffffff81216050-ffffffff8121606e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123cedd)
Location: fs/pipe.c:1098
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
```
**Symbols:**

```
ffffffff8123cea0-ffffffff8123cebe: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124fc3d)
Location: fs/pipe.c:1141
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
```
**Symbols:**

```
ffffffff8124fc00-ffffffff8124fc1e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125bb9d)
Location: fs/pipe.c:1140
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
```
**Symbols:**

```
ffffffff8125bb60-ffffffff8125bb80: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127df7d)
Location: fs/pipe.c:1147
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:vmsplice_to_user
```
**Symbols:**

```
ffffffff8127df40-ffffffff8127df60: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a4ea5)
Location: fs/pipe.c:1138
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812a4e80-ffffffff812a4e9e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b9f75)
Location: fs/pipe.c:1131
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812b9f50-ffffffff812b9f6e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d6c05)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812d6be0-ffffffff812d6bfe: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e8775)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812e8750-ffffffff812e876e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813209d5)
Location: fs/pipe.c:1350
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81320990-ffffffff813209cb: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132bf55)
Location: fs/pipe.c:1349
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8132bf10-ffffffff8132bf4b: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81331f95)
Location: fs/pipe.c:1363
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81331f50-ffffffff81331f88: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137f725)
Location: fs/pipe.c:1366
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff8137f6e0-ffffffff8137f718: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813ff885)
Location: fs/pipe.c:1372
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff813ff830-ffffffff813ff874: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81489685)
Location: fs/pipe.c:1372
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81489620-ffffffff81489664: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814be5b5)
Location: fs/pipe.c:1377
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff814be550-ffffffff814be597: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file, bool for_splice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814f0a55)
Location: fs/pipe.c:1394
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - kernel/watch_queue.c:get_watch_queue
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff814f09f0-ffffffff814f0a37: get_pipe_info (STB_GLOBAL)
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
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff8000103917ec)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffff800010391778-ffff8000103917c8: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c05780ac)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
c0578068-c0578098: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000489858)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
c000000000489800-c000000000489838: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe000260cbc)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffe000260c66-ffffffe000260c98: get_pipe_info (STB_GLOBAL)
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
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e0d55)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812e0d30-ffffffff812e0d4e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d1995)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812d1970-ffffffff812d198e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812deb65)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812deb40-ffffffff812deb5e: get_pipe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pipe_inode_info *get_pipe_info(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812efad5)
Location: fs/pipe.c:1143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff812efab0-ffffffff812eface: get_pipe_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool for_splice</code>
</li>
</ul>
</details>
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
