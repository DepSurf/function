# Function: <code>shmem_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a7200)
Location: mm/shmem.c:1424
Inline: False
Direct callers:
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
```
**Symbols:**

```
ffffffff811a7200-ffffffff811a7480: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bd770)
Location: mm/shmem.c:2080
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff811bd770-ffffffff811bda0f: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cde60)
Location: mm/shmem.c:2117
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff811cde60-ffffffff811ce068: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d6ea0)
Location: mm/shmem.c:2154
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff811d6ea0-ffffffff811d7137: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eceb0)
Location: mm/shmem.c:2165
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff811eceb0-ffffffff811ed181: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120fbb0)
Location: mm/shmem.c:2184
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff8120fbb0-ffffffff8120fe53: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81224f80)
Location: mm/shmem.c:2146
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff81224f80-ffffffff81225223: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81232150)
Location: mm/shmem.c:2226
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff81232150-ffffffff812323e1: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81240380)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff81240380-ffffffff81240611: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812712c0)
Location: mm/shmem.c:2227
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff812712c0-ffffffff812715d4: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812782e0)
Location: mm/shmem.c:2292
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff812782e0-ffffffff8127852c: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127d260)
Location: mm/shmem.c:2280
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff8127d260-ffffffff8127d4b3: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bb3e0)
Location: mm/shmem.c:2282
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff812bb3e0-ffffffff812bb636: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81315f10)
Location: mm/shmem.c:2276
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff81315f10-ffffffff8131619f: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138a060)
Location: mm/shmem.c:2330
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff8138a060-ffffffff8138a321: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *shmem_get_inode(struct mnt_idmap *idmap, struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:2360
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff813bc240-ffffffff813bc526: shmem_get_inode (STB_LOCAL)
ffffffff820e251f-ffffffff820e2534: shmem_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct mnt_idmap *idmap, struct super_block *sb, struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e6f70)
Location: mm/shmem.c:2541
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff813e6f70-ffffffff813e6fe0: shmem_get_inode (STB_LOCAL)
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
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d1dd0)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffff8000102d1dd0-ffff8000102d20a4: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04f933c)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
c04f933c-c04f9594: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038f4c0)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
c00000000038f4c0-c00000000038f880: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001eec90)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffe0001eec90-ffffffe0001eee90: shmem_get_inode (STB_LOCAL)
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
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812389d0)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff812389d0-ffffffff81238c61: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122ba10)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff8122ba10-ffffffff8122bca1: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236770)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff81236770-ffffffff81236a01: shmem_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *shmem_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81243aa0)
Location: mm/shmem.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_tmpfile
  - mm/shmem.c:shmem_mknod
```
**Symbols:**

```
ffffffff81243aa0-ffffffff81243d34: shmem_get_inode (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode *dir</code> ➡️ <code>struct inode *dir</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, dir, mode, dev, flags</code> ➡️ <code>idmap, sb, dir, mode, dev, flags</code>
</li>
</ul>
</details>
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
