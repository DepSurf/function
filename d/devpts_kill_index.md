# Function: <code>devpts_kill_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void devpts_kill_index(struct inode *ptmx_inode, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8128e2e0)
Location: fs/devpts/inode.c:567
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_shutdown
```
**Symbols:**

```
ffffffff8128e2e0-ffffffff8128e347: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812bb960)
Location: fs/devpts/inode.c:526
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff812bb960-ffffffff812bb9a1: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812d0fb0)
Location: fs/devpts/inode.c:507
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff812d0fb0-ffffffff812d0ff1: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812e2620)
Location: fs/devpts/inode.c:540
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff812e2620-ffffffff812e2661: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81307050)
Location: fs/devpts/inode.c:568
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81307050-ffffffff81307091: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81334fe0)
Location: fs/devpts/inode.c:568
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81334fe0-ffffffff81335021: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8134c2a0)
Location: fs/devpts/inode.c:550
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff8134c2a0-ffffffff8134c2b7: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81374c70)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81374c70-ffffffff81374c87: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8138cef0)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff8138cef0-ffffffff8138cf07: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813d8340)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff813d8340-ffffffff813d8357: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813e9fe0)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff813e9fe0-ffffffff813e9ff7: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813f0b20)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff813f0b20-ffffffff813f0b37: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81442a10)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81442a10-ffffffff81442a27: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff814be7a0)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff814be7a0-ffffffff814be7bf: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81556630)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81556630-ffffffff8155664f: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8158e3f0)
Location: fs/devpts/inode.c:529
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff8158e3f0-ffffffff8158e40f: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff815c7120)
Location: fs/devpts/inode.c:528
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff815c7120-ffffffff815c713f: devpts_kill_index (STB_GLOBAL)
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
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffff80001045eba0)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffff80001045eba0-ffff80001045ec0c: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c061f5f8)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
c061f5f8-c061f634: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c00000000057ad10)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
c00000000057ad10-c00000000057ad64: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffe0002ee778)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffe0002ee778-ffffffe0002ee7b8: devpts_kill_index (STB_GLOBAL)
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
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813854d0)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff813854d0-ffffffff813854e7: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81375f60)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81375f60-ffffffff81375f77: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81382fa0)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81382fa0-ffffffff81382fb7: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devpts_kill_index(struct pts_fs_info *fsi, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81396ac0)
Location: fs/devpts/inode.c:547
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_remove
```
**Symbols:**

```
ffffffff81396ac0-ffffffff81396ad7: devpts_kill_index (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pts_fs_info *fsi</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *ptmx_inode</code>
</li>
</ul>
</details>
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
