# Function: <code>ext4_reset_inode_seed</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81413f00)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81413f00-ffffffff81413fd6: ext4_reset_inode_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8141a170)
Location: fs/ext4/ioctl.c:90
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff8141a170-ffffffff8141a246: ext4_reset_inode_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8146d360)
Location: fs/ext4/ioctl.c:90
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff8146d360-ffffffff8146d436: ext4_reset_inode_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff814edbd0)
Location: fs/ext4/ioctl.c:331
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff814edbd0-ffffffff814edce4: ext4_reset_inode_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81587a80)
Location: fs/ext4/ioctl.c:340
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81587a80-ffffffff81587b94: ext4_reset_inode_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815be300)
Location: fs/ext4/ioctl.c:337
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff815be300-ffffffff815be414: ext4_reset_inode_seed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815f70c0)
Location: fs/ext4/ioctl.c:346
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff815f70c0-ffffffff815f71d4: ext4_reset_inode_seed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
