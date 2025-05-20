# Function: <code>zpool_malloc_support_movable</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812ce2e0)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812ce2e0-ffffffff812ce2f2: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81304600)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81304600-ffffffff81304612: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff813103c0)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff813103c0-ffffffff813103d2: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81316480)
Location: mm/zpool.c:254
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81316480-ffffffff81316492: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:254
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81cc3476-ffffffff81cc3496: zpool_malloc_support_movable.cold (STB_LOCAL)
ffffffff81362600-ffffffff81362618: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:242
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81e75ad3-ffffffff81e75afd: zpool_malloc_support_movable.cold (STB_LOCAL)
ffffffff813df070-ffffffff813df092: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:236
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff820684a9-ffffffff820684d3: zpool_malloc_support_movable.cold (STB_LOCAL)
ffffffff81465dd0-ffffffff81465df2: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:234
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff820e7dac-ffffffff820e7dd6: zpool_malloc_support_movable.cold (STB_LOCAL)
ffffffff8149b840-ffffffff8149b862: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:234
Inline: False
Direct callers:
  - mm/zswap.c:zswap_store
```
**Symbols:**

```
ffffffff821c4af2-ffffffff821c4b1c: zpool_malloc_support_movable.cold (STB_LOCAL)
ffffffff814caf40-ffffffff814caf62: zpool_malloc_support_movable (STB_GLOBAL)
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
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffff800010372a90)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffff800010372a90-ffff800010372abc: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c055f520)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
c055f520-c055f540: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c0000000004646f0)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
c0000000004646f0-c000000000464704: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffe00024bb68)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffe00024bb68-ffffffe00024bb8e: zpool_malloc_support_movable (STB_GLOBAL)
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
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812c68c0)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812c68c0-ffffffff812c68d2: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812b7900)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812b7900-ffffffff812b7912: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812c46d0)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812c46d0-ffffffff812c46e2: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool zpool_malloc_support_movable(struct zpool *zpool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812d5160)
Location: mm/zpool.c:252
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff812d5160-ffffffff812d5172: zpool_malloc_support_movable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
