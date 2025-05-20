# Function: <code>debugfs_real_fops</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8136a22b)
Location: include/linux/debugfs.h:56
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e89a)
Location: include/linux/debugfs.h:55
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a38a8)
Location: fs/debugfs/file.c:48
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff813a33d0-ffffffff813a33df: debugfs_real_fops.part.3 (STB_LOCAL)
ffffffff813a33e0-ffffffff813a3400: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d2c5c)
Location: fs/debugfs/file.c:48
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff813d26f0-ffffffff813d26ff: debugfs_real_fops.part.5 (STB_LOCAL)
ffffffff813d2700-ffffffff813d2720: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ed2ce)
Location: fs/debugfs/file.c:48
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff813ecde0-ffffffff813ecdef: debugfs_real_fops.part.5 (STB_LOCAL)
ffffffff813ecdf0-ffffffff813ece10: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141953f)
Location: fs/debugfs/file.c:48
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff814196eb-ffffffff81419706: debugfs_real_fops.part.0 (STB_LOCAL)
ffffffff81419706-ffffffff81419710: debugfs_real_fops.cold (STB_LOCAL)
ffffffff81418fc0-ffffffff81418fde: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143341c)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff81432e80-ffffffff81432e8f: debugfs_real_fops.part.0 (STB_LOCAL)
ffffffff81432e90-ffffffff81432eb0: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81482efd)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff81482470-ffffffff81482490: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a058d)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8149fb00-ffffffff8149fb20: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a665d)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff814a5b00-ffffffff814a5b20: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fe57c)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff814fd3c0-ffffffff814fd3e0: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158f2a0)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8158dc60-ffffffff8158dc8c: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636420)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - mm/vmscan.c:lru_gen_seq_show
```
**Symbols:**

```
ffffffff81634950-ffffffff8163497c: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166e7e3)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - mm/vmscan.c:lru_gen_seq_show
```
**Symbols:**

```
ffffffff8166cc60-ffffffff8166cc8f: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a9223)
Location: fs/debugfs/file.c:50
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - mm/vmscan.c:lru_gen_seq_show
```
**Symbols:**

```
ffffffff816a7200-ffffffff816a7232: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffff800010518d20)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffff800010518660-ffff800010518680: debugfs_real_fops.part.0 (STB_LOCAL)
ffff800010518680-ffff8000105186c4: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (c06d31f8)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
c06d2b48-c06d2b7c: debugfs_real_fops.part.0 (STB_LOCAL)
c06d2b7c-c06d2bb0: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (c0000000006620c8)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
c000000000661770-c000000000661784: debugfs_real_fops.part.0 (STB_LOCAL)
c000000000661790-c0000000006617c4: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffe000382130)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffe000381adc-ffffffe000381afa: debugfs_real_fops.part.0 (STB_LOCAL)
ffffffe000381afa-ffffffe000381b38: debugfs_real_fops (STB_GLOBAL)
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
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142b9fc)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8142b460-ffffffff8142b46f: debugfs_real_fops.part.0 (STB_LOCAL)
ffffffff8142b470-ffffffff8142b490: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141c47c)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8141bee0-ffffffff8141beef: debugfs_real_fops.part.0 (STB_LOCAL)
ffffffff8141bef0-ffffffff8141bf10: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff81427b9c)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff81427600-ffffffff8142760f: debugfs_real_fops.part.0 (STB_LOCAL)
ffffffff81427610-ffffffff81427630: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct file_operations *debugfs_real_fops(const struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143ea5c)
Location: fs/debugfs/file.c:49
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
Direct callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_release
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
**Symbols:**

```
ffffffff8143e4c0-ffffffff8143e4cf: debugfs_real_fops.part.0 (STB_LOCAL)
ffffffff8143e4d0-ffffffff8143e4f0: debugfs_real_fops (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
