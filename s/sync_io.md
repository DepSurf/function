# Function: <code>sync_io</code>

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
In drivers/md/dm-io.c (ffffffff816ab30d)
Location: drivers/md/dm-io.c:404
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
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
In drivers/md/dm-io.c (ffffffff8170b831)
Location: drivers/md/dm-io.c:407
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8173d620)
Location: drivers/md/dm-io.c:421
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff8173d620-ffffffff8173d748: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff817572e0)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff817572e0-ffffffff817573f5: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff817c9530)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff817c9530-ffffffff817c9645: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81812290)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81812290-ffffffff818123a4: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8183e210)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff8183e210-ffffffff8183e324: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81880f30-ffffffff81881040: sync_io (STB_LOCAL)
ffffffff81881333-ffffffff8188134b: sync_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818b2df0)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff818b2df0-ffffffff818b2f09: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81983430)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81983430-ffffffff81983549: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81987550)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81987550-ffffffff81987669: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8196bc20)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff8196bc20-ffffffff8196bd36: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81a140e0)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81a140e0-ffffffff81a141f6: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81b7c8f0)
Location: drivers/md/dm-io.c:413
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81b7c8f0-ffffffff81b7ca39: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, blk_opf_t opf, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d1a7b0)
Location: drivers/md/dm-io.c:414
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81d1a7b0-ffffffff81d1a8f4: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, blk_opf_t opf, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d83910)
Location: drivers/md/dm-io.c:426
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81d83910-ffffffff81d83a54: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, blk_opf_t opf, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81e3aff0)
Location: drivers/md/dm-io.c:426
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81e3aff0-ffffffff81e3b134: sync_io (STB_LOCAL)
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
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffff800010b0a538)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffff800010b0a538-ffff800010b0a668: sync_io (STB_LOCAL)
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
In drivers/md/dm-io.c (c0be8c24)
Location: drivers/md/dm-io.c:432
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (c000000000bfc070)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
c000000000bfc070-c000000000bfc214: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffe0006f850c)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffe0006f850c-ffffffe0006f85fa: sync_io (STB_LOCAL)
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
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81858c70)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81858c70-ffffffff81858d89: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81820280)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81820280-ffffffff81820399: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818a82a0)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff818a82a0-ffffffff818a83b9: sync_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sync_io(struct dm_io_client *client, unsigned int num_regions, struct dm_io_region *where, int op, int op_flags, struct dpages *dp, long unsigned int *error_bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818c44e0)
Location: drivers/md/dm-io.c:432
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff818c44e0-ffffffff818c45f9: sync_io (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>client, num_regions, where, op, op_flags, dp, error_bits</code> ➡️ <code>client, num_regions, where, opf, dp, error_bits</code>
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
