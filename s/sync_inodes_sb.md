# Function: <code>sync_inodes_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81239d80)
Location: fs/fs-writeback.c:2301
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff81239d80-ffffffff81239f68: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81261d40)
Location: fs/fs-writeback.c:2380
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff81261d40-ffffffff81261fdc: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81275240)
Location: fs/fs-writeback.c:2378
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81275240-ffffffff812754dc: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81282790)
Location: fs/fs-writeback.c:2387
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81282790-ffffffff81282a34: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a52d0)
Location: fs/fs-writeback.c:2402
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff812a52d0-ffffffff812a5574: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812cc190)
Location: fs/fs-writeback.c:2400
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff812cc190-ffffffff812cc41f: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e10d0)
Location: fs/fs-writeback.c:2426
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff812e10d0-ffffffff812e136b: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs-writeback.c (0)
Location: fs/fs-writeback.c:2441
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81302425-ffffffff8130244b: sync_inodes_sb.cold (STB_LOCAL)
ffffffff812ff830-ffffffff812ffab9: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81314740)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81314740-ffffffff813149e9: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134e210)
Location: fs/fs-writeback.c:2538
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff8134e210-ffffffff8134e304: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135b0c0)
Location: fs/fs-writeback.c:2531
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff8135b0c0-ffffffff8135b1b4: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81361cc0)
Location: fs/fs-writeback.c:2532
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff81361cc0-ffffffff81361db4: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813b0320)
Location: fs/fs-writeback.c:2672
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff813b0320-ffffffff813b0414: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81434f50)
Location: fs/fs-writeback.c:2667
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff81434f50-ffffffff81435205: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c2f90)
Location: fs/fs-writeback.c:2699
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff814c2f90-ffffffff814c3245: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f8370)
Location: fs/fs-writeback.c:2710
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff814f8370-ffffffff814f8625: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152caf0)
Location: fs/fs-writeback.c:2732
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
```
**Symbols:**

```
ffffffff8152caf0-ffffffff8152cda5: sync_inodes_sb (STB_GLOBAL)
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
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103ca5d0)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffff8000103ca5d0-ffff8000103ca8e0: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a6bc4)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
c05a6bc4-c05a6e4c: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cbf60)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
c0000000004cbf60-c0000000004cc320: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe0002887e0)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffe0002887e0-ffffffe000288aa4: sync_inodes_sb (STB_GLOBAL)
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
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130cd20)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff8130cd20-ffffffff8130cfc9: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd940)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff812fd940-ffffffff812fdbdd: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130ab10)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff8130ab10-ffffffff8130adb9: sync_inodes_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sync_inodes_sb(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131c240)
Location: fs/fs-writeback.c:2529
Inline: False
Direct callers:
  - fs/sync.c:sync_inodes_one_sb
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff8131c240-ffffffff8131c4da: sync_inodes_sb (STB_GLOBAL)
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
