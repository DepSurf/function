# Function: <code>fat_bmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff812f58c0)
Location: fs/fat/cache.c:304
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff812f58c0-ffffffff812f5a63: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81329400)
Location: fs/fat/cache.c:352
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81329400-ffffffff813294c3: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8133f140)
Location: fs/fat/cache.c:352
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff8133f140-ffffffff8133f203: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81353cd0)
Location: fs/fat/cache.c:352
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81353cd0-ffffffff81353d90: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813788f0)
Location: fs/fat/cache.c:353
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813788f0-ffffffff813789b0: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813a73e0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813a73e0-ffffffff813a749e: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813c01d0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813c01d0-ffffffff813c028e: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813ea9e0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813ea9e0-ffffffff813eaa9b: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81404a80)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81404a80-ffffffff81404b3b: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81452910)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff81452910-ffffffff814529ce: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8146edf0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff8146edf0-ffffffff8146eeae: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81474400)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff81474400-ffffffff814744be: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff81ccf884-ffffffff81ccf913: fat_bmap.cold (STB_LOCAL)
ffffffff814cb0b0-ffffffff814cb1d7: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff81e82a5a-ffffffff81e82ae0: fat_bmap.cold (STB_LOCAL)
ffffffff81557150-ffffffff8155728f: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff82071d0c-ffffffff82071d92: fat_bmap.cold (STB_LOCAL)
ffffffff815f8d10-ffffffff815f8e4f: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff820f19a1-ffffffff820f1a10: fat_bmap.cold (STB_LOCAL)
ffffffff81630c90-ffffffff81630da7: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/cache.c (0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
**Symbols:**

```
ffffffff821cec83-ffffffff821cecf2: fat_bmap.cold (STB_LOCAL)
ffffffff8166a140-ffffffff8166a257: fat_bmap (STB_GLOBAL)
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
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffff8000104e36c8)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffff8000104e36c8-ffff8000104e37dc: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (c06a2868)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
c06a2868-c06a2a34: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (c000000000620960)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
c000000000620960-c000000000620a48: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffe000356df2)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffe000356df2-ffffffe000356ec4: fat_bmap (STB_GLOBAL)
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
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813fd060)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813fd060-ffffffff813fd11b: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813edae0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813edae0-ffffffff813edb9b: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813fa3e0)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff813fa3e0-ffffffff813fa49b: fat_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_bmap(struct inode *inode, sector_t sector, sector_t *phys, long unsigned int *mapped_blocks, int create, bool from_bmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81410040)
Location: fs/fat/cache.c:358
Inline: False
Direct callers:
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
**Symbols:**

```
ffffffff81410040-ffffffff814100fb: fat_bmap (STB_GLOBAL)
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
<code>bool from_bmap</code>
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
