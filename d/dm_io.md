# Function: <code>dm_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff816ab140)
Location: drivers/md/dm-io.c:509
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff816ab140-ffffffff816ab418: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8170b650)
Location: drivers/md/dm-io.c:512
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff8170b650-ffffffff8170b944: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8173d750)
Location: drivers/md/dm-io.c:526
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff8173d750-ffffffff8173d979: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81757400)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81757400-ffffffff8175760f: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff817c9650)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff817c9650-ffffffff817c9861: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818123b0)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff818123b0-ffffffff818125cc: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8183e330)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff8183e330-ffffffff8183e54c: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff8188134b-ffffffff81881371: dm_io.cold (STB_LOCAL)
ffffffff81881040-ffffffff81881249: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818b2f10)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff818b2f10-ffffffff818b3125: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81983550)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81983550-ffffffff81983765: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81987670)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81987670-ffffffff81987885: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8196bd40)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff8196bd40-ffffffff8196bf59: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81a14200)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81a14200-ffffffff81a14419: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81b7ca40)
Location: drivers/md/dm-io.c:510
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81b7ca40-ffffffff81b7cc6b: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d1a910)
Location: drivers/md/dm-io.c:511
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81d1a910-ffffffff81d1ab3d: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d83a70)
Location: drivers/md/dm-io.c:523
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81d83a70-ffffffff81d83ca1: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81e3b150)
Location: drivers/md/dm-io.c:523
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81e3b150-ffffffff81e3b381: dm_io (STB_GLOBAL)
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
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffff800010b0a668)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffff800010b0a668-ffff800010b0a8ac: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (c0be8a30)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
c0be8a30-c0be8d2c: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (c000000000bfc220)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
c000000000bfc220-c000000000bfc504: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffe0006f85fa)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffe0006f85fa-ffffffe0006f87cc: dm_io (STB_GLOBAL)
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
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81858d90)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff81858d90-ffffffff81858fa5: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818203a0)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff818203a0-ffffffff818205b5: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818a83c0)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff818a83c0-ffffffff818a85d5: dm_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_io(struct dm_io_request *io_req, unsigned int num_regions, struct dm_io_region *where, long unsigned int *sync_error_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818c4600)
Location: drivers/md/dm-io.c:537
Inline: False
Direct callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
**Symbols:**

```
ffffffff818c4600-ffffffff818c4815: dm_io (STB_GLOBAL)
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
