# Function: <code>zpool_evictable</code>

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
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff8128c2c0)
Location: mm/zpool.c:374
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff8128c2c0-ffffffff8128c2cf: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812a1230)
Location: mm/zpool.c:374
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812a1230-ffffffff812a123f: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812bc4d0)
Location: mm/zpool.c:375
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812bc4d0-ffffffff812bc4df: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812ce3d0)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812ce3d0-ffffffff812ce3df: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff813046f0)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff813046f0-ffffffff813046ff: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff813104b0)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff813104b0-ffffffff813104bf: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81316570)
Location: mm/zpool.c:393
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81316570-ffffffff8131657f: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:393
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81cc3496-ffffffff81cc34b6: zpool_evictable.cold (STB_LOCAL)
ffffffff813626f0-ffffffff81362705: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:381
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81e75afd-ffffffff81e75b27: zpool_evictable.cold (STB_LOCAL)
ffffffff813df1d0-ffffffff813df1ef: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81465fa0)
Location: mm/zpool.c:375
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81465fa0-ffffffff81465fbc: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffff800010372c50)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffff800010372c50-ffff800010372c78: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c055f640)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
c055f640-c055f65c: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c000000000464900)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
c000000000464900-c000000000464910: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffe00024bccc)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffe00024bccc-ffffffe00024bcf0: zpool_evictable (STB_GLOBAL)
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
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812c69b0)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812c69b0-ffffffff812c69bf: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812b79f0)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812b79f0-ffffffff812b79ff: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812c47c0)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812c47c0-ffffffff812c47cf: zpool_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool zpool_evictable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812d5250)
Location: mm/zpool.c:391
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812d5250-ffffffff812d525f: zpool_evictable (STB_GLOBAL)
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
