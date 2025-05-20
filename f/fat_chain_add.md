# Function: <code>fat_chain_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff812fe2e0)
Location: fs/fat/misc.c:99
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff812fe2e0-ffffffff812fe4e7: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813322e0)
Location: fs/fat/misc.c:99
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff813322e0-ffffffff813324e2: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81348080)
Location: fs/fat/misc.c:99
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81348080-ffffffff81348282: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8135ca90)
Location: fs/fat/misc.c:99
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff8135ca90-ffffffff8135cc92: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81381790)
Location: fs/fat/misc.c:99
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81381790-ffffffff81381992: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:99
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff813b087d-ffffffff813b08b0: fat_chain_add.cold.4 (STB_LOCAL)
ffffffff813b0350-ffffffff813b051f: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:100
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff813c9edd-ffffffff813c9f10: fat_chain_add.cold.9 (STB_LOCAL)
ffffffff813c99b0-ffffffff813c9b7f: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff813f4a5d-ffffffff813f4a90: fat_chain_add.cold (STB_LOCAL)
ffffffff813f4540-ffffffff813f46f8: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff8140e92d-ffffffff8140e960: fat_chain_add.cold (STB_LOCAL)
ffffffff8140e410-ffffffff8140e5c8: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff8145c71d-ffffffff8145c750: fat_chain_add.cold (STB_LOCAL)
ffffffff8145c1f0-ffffffff8145c3a8: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81bedecc-ffffffff81bedeff: fat_chain_add.cold (STB_LOCAL)
ffffffff814780f0-ffffffff814782a8: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81bdffd6-ffffffff81be0009: fat_chain_add.cold (STB_LOCAL)
ffffffff8147db80-ffffffff8147dd34: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81cd0666-ffffffff81cd0714: fat_chain_add.cold (STB_LOCAL)
ffffffff814d5400-ffffffff814d55f3: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:107
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81e838e2-ffffffff81e8399b: fat_chain_add.cold (STB_LOCAL)
ffffffff81562440-ffffffff81562642: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:107
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff820723dc-ffffffff82072458: fat_chain_add.cold (STB_LOCAL)
ffffffff81604dd0-ffffffff81604ff1: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:107
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff820f1fff-ffffffff820f2073: fat_chain_add.cold (STB_LOCAL)
ffffffff8163cce0-ffffffff8163cf01: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:107
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff821cf2e1-ffffffff821cf355: fat_chain_add.cold (STB_LOCAL)
ffffffff81676250-ffffffff81676471: fat_chain_add (STB_GLOBAL)
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
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffff8000104eefc0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffff8000104eefc0-ffff8000104ef19c: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c06acb04)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
c06acb04-c06acd1c: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c00000000062e190)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
c00000000062e190-c00000000062e420: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffe00035f06c)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffe00035f06c-ffffffe00035f1f6: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81406f0d-ffffffff81406f40: fat_chain_add.cold (STB_LOCAL)
ffffffff814069f0-ffffffff81406ba8: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff813f798d-ffffffff813f79c0: fat_chain_add.cold (STB_LOCAL)
ffffffff813f7470-ffffffff813f7628: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff8140428d-ffffffff814042c0: fat_chain_add.cold (STB_LOCAL)
ffffffff81403d70-ffffffff81403f28: fat_chain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_chain_add(struct inode *inode, int new_dclus, int nr_cluster);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/misc.c (0)
Location: fs/fat/misc.c:101
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/inode.c:fat_add_cluster
```
**Symbols:**

```
ffffffff81419ef0-ffffffff81419f23: fat_chain_add.cold (STB_LOCAL)
ffffffff814199e0-ffffffff81419b98: fat_chain_add (STB_GLOBAL)
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
