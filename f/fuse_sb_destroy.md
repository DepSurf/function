# Function: <code>fuse_sb_destroy</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813cd9e0)
Location: fs/fuse/inode.c:1216
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff813cd9e0-ffffffff813cda80: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e6dd0)
Location: fs/fuse/inode.c:1238
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff813e6dd0-ffffffff813e6e70: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81412e00)
Location: fs/fuse/inode.c:1239
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81412e00-ffffffff81412e9e: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142d750)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff8142d750-ffffffff8142d7b2: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147cea0)
Location: fs/fuse/inode.c:1341
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff8147cea0-ffffffff8147cefc: fuse_sb_destroy.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149821a)
Location: fs/fuse/inode.c:1559
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149d44a)
Location: fs/fuse/inode.c:1601
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f4ea5)
Location: fs/fuse/inode.c:1730
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81584dc5)
Location: fs/fuse/inode.c:1786
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162af55)
Location: fs/fuse/inode.c:1791
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81663175)
Location: fs/fuse/inode.c:1797
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169d2e5)
Location: fs/fuse/inode.c:1897
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
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
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010511540)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffff800010511540-ffff8000105115a8: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06ccdfc)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
c06ccdfc-c06ccecc: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c000000000659410)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
c000000000659410-c0000000006594ac: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037bcfe)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffe00037bcfe-ffffffe00037bd6c: fuse_sb_destroy (STB_LOCAL)
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
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81425d30)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81425d30-ffffffff81425d92: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814167b0)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff814167b0-ffffffff81416812: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81421ed0)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81421ed0-ffffffff81421f32: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_sb_destroy(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81438d50)
Location: fs/fuse/inode.c:1321
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81438d50-ffffffff81438db2: fuse_sb_destroy (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
