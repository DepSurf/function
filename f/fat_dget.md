# Function: <code>fat_dget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff812fe6b0)
Location: fs/fat/nfs.c:32
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff812fe6b0-ffffffff812fe754: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813326b0)
Location: fs/fat/nfs.c:32
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813326b0-ffffffff81332754: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81348450)
Location: fs/fat/nfs.c:32
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81348450-ffffffff813484f4: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8135cfc0)
Location: fs/fat/nfs.c:32
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8135cfc0-ffffffff8135d06b: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81381cc0)
Location: fs/fat/nfs.c:32
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81381cc0-ffffffff81381d6b: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813b0a90)
Location: fs/fat/nfs.c:32
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813b0a90-ffffffff813b0b3b: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813ca190)
Location: fs/fat/nfs.c:32
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813ca190-ffffffff813ca23b: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813f4d10)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813f4d10-ffffffff813f4dad: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8140ebe0)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8140ebe0-ffffffff8140ec7d: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8145c750)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff8145c750-ffffffff8145c7ed: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81478480)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81478480-ffffffff8147851d: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8147def0)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff8147def0-ffffffff8147df8d: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff814d5690)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff814d5690-ffffffff814d572d: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81562770)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81562770-ffffffff8156281c: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81605160)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81605160-ffffffff8160520c: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8163d070)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff8163d070-ffffffff8163d11c: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff816765e0)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff816765e0-ffffffff8167668c: fat_dget (STB_LOCAL)
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
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffff8000104efa08)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffff8000104efa08-ffff8000104efb00: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c06ad048)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
c06ad048-c06ad108: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c00000000062e860)
Location: fs/fat/nfs.c:23
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
c00000000062e860-c00000000062e988: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffe00035f834)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffe00035f834-ffffffe00035f906: fat_dget (STB_LOCAL)
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
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff814071c0)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff814071c0-ffffffff8140725d: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813f7c40)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff813f7c40-ffffffff813f7cdd: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81404540)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81404540-ffffffff814045dd: fat_dget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_dget(struct super_block *sb, int i_logstart);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8141a1b0)
Location: fs/fat/nfs.c:23
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8141a1b0-ffffffff8141a254: fat_dget (STB_LOCAL)
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
