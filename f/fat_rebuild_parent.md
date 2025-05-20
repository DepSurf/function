# Function: <code>fat_rebuild_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff812fe82b)
Location: fs/fat/nfs.c:223
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81332815)
Location: fs/fat/nfs.c:223
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813485b5)
Location: fs/fat/nfs.c:223
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
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
In fs/fat/nfs.c (ffffffff8135d11c)
Location: fs/fat/nfs.c:223
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81381e1c)
Location: fs/fat/nfs.c:223
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813b0c01)
Location: fs/fat/nfs.c:223
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813ca301)
Location: fs/fat/nfs.c:223
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813f4e6f)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8140ed3f)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8145c7f0-ffffffff8145c937: fat_rebuild_parent (STB_LOCAL)
ffffffff8145ccd4-ffffffff8145ccf2: fat_rebuild_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81478520-ffffffff81478667: fat_rebuild_parent (STB_LOCAL)
ffffffff81bedeff-ffffffff81bedf1d: fat_rebuild_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8147df90-ffffffff8147e0d7: fat_rebuild_parent (STB_LOCAL)
ffffffff81be0009-ffffffff81be0027: fat_rebuild_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff814d5730-ffffffff814d5877: fat_rebuild_parent (STB_LOCAL)
ffffffff81cd0714-ffffffff81cd0732: fat_rebuild_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81562820-ffffffff8156299b: fat_rebuild_parent (STB_LOCAL)
ffffffff81e8399b-ffffffff81e839b6: fat_rebuild_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81605220)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff81605220-ffffffff816053bc: fat_rebuild_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8163d130)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff8163d130-ffffffff8163d2cc: fat_rebuild_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *fat_rebuild_parent(struct super_block *sb, int parent_logstart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff816766a0)
Location: fs/fat/nfs.c:214
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_get_parent
```
**Symbols:**

```
ffffffff816766a0-ffffffff8167683c: fat_rebuild_parent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffff8000104efbd0)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c06ad1d4)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c00000000062eab0)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffe00035f978)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8140731f)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff813f7d9f)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8140469f)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8141a31f)
Location: fs/fat/nfs.c:214
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
