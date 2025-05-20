# Function: <code>mpage_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8124d500)
Location: fs/mpage.c:67
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8124d500-ffffffff8124d580: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81275bf0)
Location: fs/mpage.c:69
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81275bf0-ffffffff81275c76: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81289920)
Location: fs/mpage.c:69
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81289920-ffffffff812899a6: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81296620)
Location: fs/mpage.c:70
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81296620-ffffffff812966a6: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff812b99b0)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812b99b0-ffffffff812b9a65: mpage_alloc.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff812e2520)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812e2520-ffffffff812e25da: mpage_alloc.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff812f7170)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812f7170-ffffffff812f7232: mpage_alloc.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff813177a0)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813177a0-ffffffff8131785d: mpage_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff8132a620)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8132a620-ffffffff8132a6dd: mpage_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81364130)
Location: fs/mpage.c:71
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81364130-ffffffff813641e2: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81371030)
Location: fs/mpage.c:71
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81371030-ffffffff813710e5: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813779f0)
Location: fs/mpage.c:71
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813779f0-ffffffff81377a9b: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813c4070)
Location: fs/mpage.c:71
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813c4070-ffffffff813c411b: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffff8000103e5da0)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffff8000103e5da0-ffff8000103e5e8c: mpage_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (c05bd70c)
Location: fs/mpage.c:71
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
c05bd70c-c05bd7e0: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (c0000000004ebc40)
Location: fs/mpage.c:71
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
c0000000004ebc40-c0000000004ebd54: mpage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *mpage_alloc(struct block_device *bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffe00029b078)
Location: fs/mpage.c:71
Inline: False
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffe00029b078-ffffffe00029b148: mpage_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff81322c00)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81322c00-ffffffff81322cbd: mpage_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff813137a0)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813137a0-ffffffff8131385d: mpage_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff813206d0)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813206d0-ffffffff8132078d: mpage_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (ffffffff813323f0)
Location: fs/mpage.c:71
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff813323f0-ffffffff813324ad: mpage_alloc.isra.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
