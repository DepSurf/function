# Function: <code>adjust_inuse_and_calc_cost</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq *iocg, u64 vtime, u64 abs_cost, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81590280)
Location: block/blk-iocost.c:2409
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff81590280-ffffffff815904eb: adjust_inuse_and_calc_cost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq *iocg, u64 vtime, u64 abs_cost, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81597030)
Location: block/blk-iocost.c:2416
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff81597030-ffffffff8159729b: adjust_inuse_and_calc_cost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq *iocg, u64 vtime, u64 abs_cost, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2423
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff815fe640-ffffffff815fe8b1: adjust_inuse_and_calc_cost (STB_LOCAL)
ffffffff81cd9ecd-ffffffff81cd9ef0: adjust_inuse_and_calc_cost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq *iocg, u64 vtime, u64 abs_cost, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2426
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff816b1d60-ffffffff816b2020: adjust_inuse_and_calc_cost (STB_LOCAL)
ffffffff81e8d9e6-ffffffff81e8da09: adjust_inuse_and_calc_cost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq *iocg, u64 vtime, u64 abs_cost, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2433
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff817709b0-ffffffff81770c7a: adjust_inuse_and_calc_cost (STB_LOCAL)
ffffffff82076f2c-ffffffff82076f4f: adjust_inuse_and_calc_cost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq *iocg, u64 vtime, u64 abs_cost, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2449
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff817b0560-ffffffff817b082a: adjust_inuse_and_calc_cost (STB_LOCAL)
ffffffff820f6db0-ffffffff820f6dd3: adjust_inuse_and_calc_cost.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq *iocg, u64 vtime, u64 abs_cost, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2456
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff817f4370-ffffffff817f463a: adjust_inuse_and_calc_cost (STB_LOCAL)
ffffffff821d41fe-ffffffff821d4221: adjust_inuse_and_calc_cost.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
