# Function: <code>ioc_lat_stat</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151285f)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioc_lat_stat(struct ioc *ioc, u32 *missed_ppm_ar, u32 *rq_wait_pct_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815712f0)
Location: block/blk-iocost.c:1270
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff815712f0-ffffffff81571455: ioc_lat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioc_lat_stat(struct ioc *ioc, u32 *missed_ppm_ar, u32 *rq_wait_pct_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158c420)
Location: block/blk-iocost.c:1554
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8158c420-ffffffff8158c588: ioc_lat_stat (STB_LOCAL)
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
In block/blk-iocost.c (ffffffff8159790d)
Location: block/blk-iocost.c:1561
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffff815ff025)
Location: block/blk-iocost.c:1561
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffff816b0f8f)
Location: block/blk-iocost.c:1560
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ioc_lat_stat(struct ioc *ioc, u32 *missed_ppm_ar, u32 *rq_wait_pct_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176cae0)
Location: block/blk-iocost.c:1565
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8176cae0-ffffffff8176ccbb: ioc_lat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ioc_lat_stat(struct ioc *ioc, u32 *missed_ppm_ar, u32 *rq_wait_pct_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ac580)
Location: block/blk-iocost.c:1581
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817ac580-ffffffff817ac75b: ioc_lat_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ioc_lat_stat(struct ioc *ioc, u32 *missed_ppm_ar, u32 *rq_wait_pct_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817f0350)
Location: block/blk-iocost.c:1588
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff817f0350-ffffffff817f052b: ioc_lat_stat (STB_LOCAL)
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
In block/blk-iocost.c (ffff800010616bc4)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (c07c18f8)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (c0000000007b625c)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffe00044d3b2)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffff8150ae3f)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffff814fb29f)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffff81506ecf)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In block/blk-iocost.c (ffffffff8152037f)
Location: block/blk-iocost.c:1271
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
