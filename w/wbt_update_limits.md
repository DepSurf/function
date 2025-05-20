# Function: <code>wbt_update_limits</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144ad8f)
Location: block/blk-wbt.c:473
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_queue_depth
Direct callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
**Symbols:**

```
ffffffff8144a850-ffffffff8144a878: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81459028)
Location: block/blk-wbt.c:460
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
**Symbols:**

```
ffffffff81458b00-ffffffff81458b28: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81484d85)
Location: block/blk-wbt.c:459
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
**Symbols:**

```
ffffffff81484860-ffffffff81484888: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b9c89)
Location: block/blk-wbt.c:488
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
**Symbols:**

```
ffffffff814b9660-ffffffff814b9688: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cdb70)
Location: block/blk-wbt.c:418
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
**Symbols:**

```
ffffffff814cdb70-ffffffff814cdba1: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fc410)
Location: block/blk-wbt.c:419
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
**Symbols:**

```
ffffffff814fc410-ffffffff814fc441: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8151a3a0)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
ffffffff8151a3a0-ffffffff8151a3d1: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8157a250)
Location: block/blk-wbt.c:408
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff8157a250-ffffffff8157a2eb: wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81597146)
Location: block/blk-wbt.c:408
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159df06)
Location: block/blk-wbt.c:409
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816065e6)
Location: block/blk-wbt.c:412
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816ba356)
Location: block/blk-wbt.c:412
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a8d6)
Location: block/blk-wbt.c:413
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba820)
Location: block/blk-wbt.c:480
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff817ba820-ffffffff817ba8df: wbt_update_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wbt_update_limits(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fef90)
Location: block/blk-wbt.c:479
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
```
**Symbols:**

```
ffffffff817fef90-ffffffff817ff04f: wbt_update_limits (STB_LOCAL)
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
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010622228)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
ffff800010622228-ffff800010622270: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c9df0)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
c07c9df0-c07c9e28: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c2300)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
c0000000007c2300-c0000000007c2330: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000454264)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
ffffffe000454264-ffffffe00045429e: wbt_update_limits (STB_GLOBAL)
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
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81512980)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
ffffffff81512980-ffffffff815129b1: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502ca0)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
ffffffff81502ca0-ffffffff81502cd1: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150ea10)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
ffffffff8150ea10-ffffffff8150ea41: wbt_update_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wbt_update_limits(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815281e0)
Location: block/blk-wbt.c:421
Inline: False
```
**Symbols:**

```
ffffffff815281e0-ffffffff81528211: wbt_update_limits (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb *rwb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_wb *rwb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
</ul>
</details>
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
