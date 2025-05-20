# Function: <code>blkif_completion</code>

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
In drivers/block/xen-blkfront.c (ffffffff81573e3f)
Location: drivers/block/xen-blkfront.c:1212
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In drivers/block/xen-blkfront.c (ffffffff815cae60)
Location: drivers/block/xen-blkfront.c:1410
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In drivers/block/xen-blkfront.c (ffffffff815f7aa0)
Location: drivers/block/xen-blkfront.c:1409
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In drivers/block/xen-blkfront.c (ffffffff8160b956)
Location: drivers/block/xen-blkfront.c:1419
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In drivers/block/xen-blkfront.c (ffffffff8167431a)
Location: drivers/block/xen-blkfront.c:1419
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In drivers/block/xen-blkfront.c (ffffffff816b04aa)
Location: drivers/block/xen-blkfront.c:1419
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In drivers/block/xen-blkfront.c (ffffffff816d0677)
Location: drivers/block/xen-blkfront.c:1418
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1418
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff8170c010-ffffffff8170c549: blkif_completion.isra.0 (STB_LOCAL)
ffffffff8170fb6f-ffffffff8170fba8: blkif_completion.isra.0.cold (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1418
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff81730310-ffffffff81730849: blkif_completion.isra.0 (STB_LOCAL)
ffffffff81733e6f-ffffffff81733ea8: blkif_completion.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1428
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff817eea70-ffffffff817eef95: blkif_completion (STB_LOCAL)
ffffffff817f1518-ffffffff817f1551: blkif_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1428
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff81803370-ffffffff81803895: blkif_completion (STB_LOCAL)
ffffffff81c0fbfb-ffffffff81c0fc34: blkif_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1428
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff817e7b30-ffffffff817e805b: blkif_completion (STB_LOCAL)
ffffffff81c01d2e-ffffffff81c01d67: blkif_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1385
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff81873b70-ffffffff8187401d: blkif_completion (STB_LOCAL)
ffffffff81d05b25-ffffffff81d05b51: blkif_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1379
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff819bb5a0-ffffffff819bba93: blkif_completion (STB_LOCAL)
ffffffff81ece410-ffffffff81ece426: blkif_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b30af0)
Location: drivers/block/xen-blkfront.c:1382
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff81b30af0-ffffffff81b30ff4: blkif_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b841b0)
Location: drivers/block/xen-blkfront.c:1383
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff81b841b0-ffffffff81b846c1: blkif_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkif_completion(long unsigned int *id, struct blkfront_ring_info *rinfo, struct blkif_response *bret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd80e0)
Location: drivers/block/xen-blkfront.c:1383
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff81bd80e0-ffffffff81bd85f1: blkif_completion (STB_LOCAL)
```
</details>
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
In drivers/block/xen-blkfront.c (ffff800010928688)
Location: drivers/block/xen-blkfront.c:1418
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffff800010928688-ffff800010928ba0: blkif_completion.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1441
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff816f60a0-ffffffff816f65d9: blkif_completion.isra.0 (STB_LOCAL)
ffffffff816f9f03-ffffffff816f9f3c: blkif_completion.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1418
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff817237d0-ffffffff81723d09: blkif_completion.isra.0 (STB_LOCAL)
ffffffff8172732f-ffffffff81727368: blkif_completion.isra.0.cold (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1418
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff8173ec40-ffffffff8173f193: blkif_completion.isra.0 (STB_LOCAL)
ffffffff8174277f-ffffffff817427b8: blkif_completion.isra.0.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
