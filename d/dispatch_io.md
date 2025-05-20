# Function: <code>dispatch_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dispatch_io(int rw, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff816aadd0)
Location: drivers/md/dm-io.c:362
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff816aadd0-ffffffff816ab13f: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8170b260)
Location: drivers/md/dm-io.c:365
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff8170b260-ffffffff8170b646: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8173d1f0)
Location: drivers/md/dm-io.c:379
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff8173d1f0-ffffffff8173d61d: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81756ea0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81756ea0-ffffffff817572d5: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff817c90b0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff817c90b0-ffffffff817c9524: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81811e40-ffffffff8181228b: dispatch_io (STB_LOCAL)
ffffffff818126a2-ffffffff818126b3: dispatch_io.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff8183ddd0-ffffffff8183e201: dispatch_io (STB_LOCAL)
ffffffff8183e622-ffffffff8183e633: dispatch_io.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81880aa0-ffffffff81880f29: dispatch_io (STB_LOCAL)
ffffffff81881322-ffffffff81881333: dispatch_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff818b2960-ffffffff818b2de8: dispatch_io (STB_LOCAL)
ffffffff818b3202-ffffffff818b3213: dispatch_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81983300)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81983300-ffffffff81983427: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81987420)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81987420-ffffffff81987547: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8196baf0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff8196baf0-ffffffff8196bc17: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81a13fb0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81a13fb0-ffffffff81a140d7: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81b7c7b0)
Location: drivers/md/dm-io.c:371
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81b7c7b0-ffffffff81b7c8eb: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dispatch_io(blk_opf_t opf, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d1a660)
Location: drivers/md/dm-io.c:372
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81d1a660-ffffffff81d1a792: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dispatch_io(blk_opf_t opf, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d837c0)
Location: drivers/md/dm-io.c:384
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81d837c0-ffffffff81d838f3: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dispatch_io(blk_opf_t opf, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81e3aea0)
Location: drivers/md/dm-io.c:384
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81e3aea0-ffffffff81e3afd3: dispatch_io (STB_LOCAL)
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffff800010b0a148)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffff800010b0a148-ffff800010b0a538: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (c0be85c8)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
c0be85c8-c0be8a30: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (c000000000bfbac0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
c000000000bfbac0-c000000000bfc070: dispatch_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffe0006f814a)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffe0006f814a-ffffffe0006f850c: dispatch_io (STB_LOCAL)
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff818587e0-ffffffff81858c68: dispatch_io (STB_LOCAL)
ffffffff81859082-ffffffff81859093: dispatch_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff8181fdf0-ffffffff81820278: dispatch_io (STB_LOCAL)
ffffffff81820692-ffffffff818206a3: dispatch_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff818a7e10-ffffffff818a8298: dispatch_io (STB_LOCAL)
ffffffff818a86b2-ffffffff818a86c3: dispatch_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region *where, struct dpages *dp, struct io *io, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:390
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff818c4050-ffffffff818c44d8: dispatch_io (STB_LOCAL)
ffffffff818c48f2-ffffffff818c4903: dispatch_io.cold (STB_LOCAL)
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
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, num_regions, where, dp, io, sync</code> ➡️ <code>op, op_flags, num_regions, where, dp, io, sync</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, num_regions, where, dp, io, sync</code> ➡️ <code>opf, num_regions, where, dp, io, sync</code>
</li>
</ul>
</details>
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
