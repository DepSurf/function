# Function: <code>squashfs_cache_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81321690)
Location: fs/squashfs/cache.c:210
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81321690-ffffffff8132173e: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81337520)
Location: fs/squashfs/cache.c:210
Inline: False
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81337520-ffffffff813375ce: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8134c4f5)
Location: fs/squashfs/cache.c:210
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8134bd70-ffffffff8134be14: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff8134c2e0-ffffffff8134c2f7: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81370b75)
Location: fs/squashfs/cache.c:210
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813703f0-ffffffff81370494: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff81370960-ffffffff81370977: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8139f703)
Location: fs/squashfs/cache.c:210
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8139ebb0-ffffffff8139ec58: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff8139f1c0-ffffffff8139f1d6: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813b8493)
Location: fs/squashfs/cache.c:210
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813b7940-ffffffff813b79e8: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff813b7f50-ffffffff813b7f66: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e2c73)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813e2110-ffffffff813e21b8: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff813e2720-ffffffff813e2736: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813fcca3)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813fc140-ffffffff813fc1e8: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff813fc750-ffffffff813fc766: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8144a613)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81449aa0-ffffffff81449b48: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff8144a0c0-ffffffff8144a0d6: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81bed3fc)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff814661c0-ffffffff81466268: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff814667b0-ffffffff814667c6: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81bdf4e0)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8146b950-ffffffff8146b9f8: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff8146bd80-ffffffff8146bd96: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81ccef2d)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff814c21b0-ffffffff814c2258: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff814c25e0-ffffffff814c25f6: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81e81f80)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8154cc00-ffffffff8154ccb2: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff8154d0e0-ffffffff8154d102: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff815ed1e5)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff815ecaf0-ffffffff815ecba2: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff815ed010-ffffffff815ed032: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff81625122)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff81624a40-ffffffff81624aed: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff81624f50-ffffffff81624f72: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff8165e22b)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff8165dad0-ffffffff8165db7d: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff8165dfe0-ffffffff8165e002: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffff8000104da7c0)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffff8000104d9e98-ffff8000104d9f88: squashfs_cache_delete.part.0 (STB_LOCAL)
ffff8000104da5a0-ffff8000104da5d0: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (c069bed4)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
c069b6e4-c069b798: squashfs_cache_delete.part.0 (STB_LOCAL)
c069bcf4-c069bd18: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (c000000000615478)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
c000000000614820-c000000000614958: squashfs_cache_delete.part.0 (STB_LOCAL)
c0000000006151d0-c0000000006151ec: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffe00034f776)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffe00034eeca-ffffffe00034ef9a: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffe00034f586-ffffffe00034f5b2: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f5283)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813f4720-ffffffff813f47c8: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff813f4d30-ffffffff813f4d46: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813e5d03)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813e51a0-ffffffff813e5248: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff813e57b0-ffffffff813e57c6: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff813f2603)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff813f1aa0-ffffffff813f1b48: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff813f20b0-ffffffff813f20c6: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void squashfs_cache_delete(struct squashfs_cache *cache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/cache.c (ffffffff814081f3)
Location: fs/squashfs/cache.c:197
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
Direct callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_put_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
```
**Symbols:**

```
ffffffff814076a0-ffffffff81407748: squashfs_cache_delete.part.0 (STB_LOCAL)
ffffffff81407ca0-ffffffff81407cb6: squashfs_cache_delete (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
