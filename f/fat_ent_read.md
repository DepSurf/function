# Function: <code>fat_ent_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff812f9820)
Location: fs/fat/fatent.c:348
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff812f9820-ffffffff812f99e8: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8132d450)
Location: fs/fat/fatent.c:348
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8132d450-ffffffff8132d618: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81343190)
Location: fs/fat/fatent.c:348
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81343190-ffffffff81343358: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81357bf0)
Location: fs/fat/fatent.c:348
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81357bf0-ffffffff81357e08: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8137c8a0)
Location: fs/fat/fatent.c:348
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8137c8a0-ffffffff8137cad0: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ab330)
Location: fs/fat/fatent.c:348
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813ab330-ffffffff813ab522: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813c5435-ffffffff813c54b2: fat_ent_read.cold.22 (STB_LOCAL)
ffffffff813c4190-ffffffff813c4359: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813eff46-ffffffff813effcf: fat_ent_read.cold (STB_LOCAL)
ffffffff813eea70-ffffffff813eec4d: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81409e31-ffffffff81409eba: fat_ent_read.cold (STB_LOCAL)
ffffffff81408ae0-ffffffff81408cbd: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81456730)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81456730-ffffffff81456936: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81472af0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81472af0-ffffffff81472cf6: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81478510)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81478510-ffffffff81478716: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff814cf8f0)
Location: fs/fat/fatent.c:348
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff814cf8f0-ffffffff814cfb0d: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8155c3b0)
Location: fs/fat/fatent.c:349
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8155c3b0-ffffffff8155c5be: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff815fe310)
Location: fs/fat/fatent.c:349
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff815fe310-ffffffff815fe592: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff816362e0)
Location: fs/fat/fatent.c:349
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff816362e0-ffffffff81636562: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8166f7d0)
Location: fs/fat/fatent.c:349
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8166f7d0-ffffffff8166fa52: fat_ent_read (STB_GLOBAL)
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
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffff8000104e9248)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffff8000104e9248-ffff8000104e9460: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c06a6ef0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
c06a6ef0-c06a7164: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c000000000626ba0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
c000000000626ba0-c000000000626ea4: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffe00035a3bc)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffe00035a3bc-ffffffe00035a556: fat_ent_read (STB_GLOBAL)
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
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81402411-ffffffff8140249a: fat_ent_read.cold (STB_LOCAL)
ffffffff814010c0-ffffffff8140129d: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813f2e91-ffffffff813f2f1a: fat_ent_read.cold (STB_LOCAL)
ffffffff813f1b40-ffffffff813f1d1d: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813ff791-ffffffff813ff81a: fat_ent_read.cold (STB_LOCAL)
ffffffff813fe440-ffffffff813fe61d: fat_ent_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_ent_read(struct inode *inode, struct fat_entry *fatent, int entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:347
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff814153bc-ffffffff81415445: fat_ent_read.cold (STB_LOCAL)
ffffffff81414060-ffffffff8141423d: fat_ent_read (STB_GLOBAL)
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
