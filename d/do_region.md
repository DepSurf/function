# Function: <code>do_region</code>

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
In drivers/md/dm-io.c (ffffffff816aaed5)
Location: drivers/md/dm-io.c:281
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm-io.c (ffffffff8170b31c)
Location: drivers/md/dm-io.c:281
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8173d30e)
Location: drivers/md/dm-io.c:295
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81756f40)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff817c9150)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81811f7f)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8183deea)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81880bcb)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818b2a8b)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void do_region(int op, int op_flags, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:296
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81982ff0-ffffffff819832fd: do_region (STB_LOCAL)
ffffffff819838f2-ffffffff81983903: do_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_region(int op, int op_flags, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:296
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81987110-ffffffff8198741d: do_region (STB_LOCAL)
ffffffff81c28676-ffffffff81c28687: do_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_region(int op, int op_flags, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:296
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff8196b7e0-ffffffff8196bae2: do_region (STB_LOCAL)
ffffffff81c1a855-ffffffff81c1a866: do_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_region(int op, int op_flags, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:296
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81a13ca0-ffffffff81a13fa2: do_region (STB_LOCAL)
ffffffff81d2a6bc-ffffffff81d2a6cd: do_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_region(int op, int op_flags, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io.c (0)
Location: drivers/md/dm-io.c:296
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81b7c5a0-ffffffff81b7c7ae: do_region (STB_LOCAL)
ffffffff81ef68d4-ffffffff81ef68e5: do_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_region(const blk_opf_t opf, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d1a3f0)
Location: drivers/md/dm-io.c:296
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81d1a3f0-ffffffff81d1a644: do_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_region(const blk_opf_t opf, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81d83550)
Location: drivers/md/dm-io.c:306
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81d83550-ffffffff81d837a1: do_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_region(const blk_opf_t opf, unsigned int region, struct dm_io_region *where, struct dpages *dp, struct io *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff81e3ac30)
Location: drivers/md/dm-io.c:306
Inline: False
Direct callers:
  - drivers/md/dm-io.c:dispatch_io
```
**Symbols:**

```
ffffffff81e3ac30-ffffffff81e3ae81: do_region (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffff800010b0a21c)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm-io.c (c0be86bc)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (c000000000bfbc58)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffe0006f81e8)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8185890b)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff8181ff1b)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818a7f3b)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-io.c (ffffffff818c417b)
Location: drivers/md/dm-io.c:296
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>const blk_opf_t opf</code>
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
<code>op, op_flags, region, where, dp, io</code> ➡️ <code>opf, region, where, dp, io</code>
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
