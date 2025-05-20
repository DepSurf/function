# Function: <code>devpts_mntget</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812e23d0)
Location: fs/devpts/inode.c:159
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff812e23d0-ffffffff812e2476: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81306db0)
Location: fs/devpts/inode.c:173
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81306db0-ffffffff81306e92: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81334d40)
Location: fs/devpts/inode.c:173
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81334d40-ffffffff81334e21: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8134c090)
Location: fs/devpts/inode.c:171
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8134c090-ffffffff8134c171: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81374a60)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81374a60-ffffffff81374b45: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8138cce0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8138cce0-ffffffff8138cdc5: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813d80e0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff813d80e0-ffffffff813d8205: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813e9d80)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff813e9d80-ffffffff813e9ea5: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813f08c0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff813f08c0-ffffffff813f09e5: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff814427b0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff814427b0-ffffffff814428d5: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff814be520)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff814be520-ffffffff814be64f: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81556370)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81556370-ffffffff8155649f: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8158e120)
Location: fs/devpts/inode.c:150
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff8158e120-ffffffff8158e255: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff815c6e50)
Location: fs/devpts/inode.c:149
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff815c6e50-ffffffff815c6f85: devpts_mntget (STB_GLOBAL)
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
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffff80001045e8b0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffff80001045e8b0-ffff80001045e9c4: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c061f360)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
c061f360-c061f470: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c00000000057a9b0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
c00000000057a9b0-c00000000057ab10: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffe0002ee572)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffe0002ee572-ffffffe0002ee650: devpts_mntget (STB_GLOBAL)
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
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813852c0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff813852c0-ffffffff813853a5: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81375d50)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81375d50-ffffffff81375e35: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81382d90)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff81382d90-ffffffff81382e75: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfsmount *devpts_mntget(struct file *filp, struct pts_fs_info *fsi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813968b0)
Location: fs/devpts/inode.c:168
Inline: False
Direct callers:
  - drivers/tty/pty.c:ptm_open_peer
```
**Symbols:**

```
ffffffff813968b0-ffffffff81396995: devpts_mntget (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
