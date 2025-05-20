# Function: <code>calc_lcoefs</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81510530)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
ffffffff81510530-ffffffff815105c6: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815706e0)
Location: block/blk-iocost.c:779
Inline: False
```
**Symbols:**

```
ffffffff815706e0-ffffffff81570779: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158b880)
Location: block/blk-iocost.c:866
Inline: False
```
**Symbols:**

```
ffffffff8158b880-ffffffff8158b919: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81592700)
Location: block/blk-iocost.c:866
Inline: False
```
**Symbols:**

```
ffffffff81592700-ffffffff8159279f: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815f9a80)
Location: block/blk-iocost.c:866
Inline: False
```
**Symbols:**

```
ffffffff815f9a80-ffffffff815f9b1f: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816abbf0)
Location: block/blk-iocost.c:865
Inline: False
```
**Symbols:**

```
ffffffff816abbf0-ffffffff816abc9a: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176a5c0)
Location: block/blk-iocost.c:862
Inline: False
```
**Symbols:**

```
ffffffff8176a5c0-ffffffff8176a67f: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817a96c0)
Location: block/blk-iocost.c:868
Inline: False
```
**Symbols:**

```
ffffffff817a96c0-ffffffff817a977f: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ed480)
Location: block/blk-iocost.c:868
Inline: False
```
**Symbols:**

```
ffffffff817ed480-ffffffff817ed53f: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010613f60)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
ffff800010613f60-ffff800010614020: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07be2c0)
Location: block/blk-iocost.c:781
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
c07be2c0-c07be3cc: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b33c0)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
c0000000007b33c0-c0000000007b3464: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044b6fc)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
ffffffe00044b6fc-ffffffe00044b79e: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508b10)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
ffffffff81508b10-ffffffff81508ba6: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f8fc0)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
ffffffff814f8fc0-ffffffff814f9056: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504ba0)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
ffffffff81504ba0-ffffffff81504c36: calc_lcoefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 *page, u64 *seqio, u64 *randio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151e1c0)
Location: block/blk-iocost.c:781
Inline: True
Direct callers:
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-iocost.c:ioc_refresh_params
```
**Symbols:**

```
ffffffff8151e1c0-ffffffff8151e256: calc_lcoefs (STB_LOCAL)
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
