# Function: <code>weight_updated</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815109b0)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff815109b0-ffffffff81510a32: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81572480)
Location: block/blk-iocost.c:1009
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff81572480-ffffffff81572524: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158e440)
Location: block/blk-iocost.c:1220
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff8158e440-ffffffff8158e4d1: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815951a0)
Location: block/blk-iocost.c:1226
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff815951a0-ffffffff81595231: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void weight_updated(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1226
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff815fc060-ffffffff815fc134: weight_updated (STB_LOCAL)
ffffffff81cd9e38-ffffffff81cd9e4d: weight_updated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void weight_updated(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1225
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff816b03f0-ffffffff816b04d9: weight_updated (STB_LOCAL)
ffffffff81e8d986-ffffffff81e8d99b: weight_updated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void weight_updated(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1230
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff81770250-ffffffff81770339: weight_updated (STB_LOCAL)
ffffffff82076efc-ffffffff82076f11: weight_updated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void weight_updated(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1246
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff817af280-ffffffff817af369: weight_updated (STB_LOCAL)
ffffffff820f6d6c-ffffffff820f6d81: weight_updated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void weight_updated(struct ioc_gq *iocg, struct ioc_now *now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:1246
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff817f3090-ffffffff817f3179: weight_updated (STB_LOCAL)
ffffffff821d41ba-ffffffff821d41cf: weight_updated.cold (STB_LOCAL)
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
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff8000106148f8)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffff8000106148f8-ffff800010614998: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bf674)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
c07bf674-c07bf718: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b3970)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
c0000000007b3970-c0000000007b3a48: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044a994)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffe00044a994-ffffffe00044aa3e: weight_updated (STB_LOCAL)
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
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508f90)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff81508f90-ffffffff81509012: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9440)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff814f9440-ffffffff814f94c2: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81505020)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff81505020-ffffffff815050a2: weight_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void weight_updated(struct ioc_gq *iocg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151e680)
Location: block/blk-iocost.c:1011
Inline: False
Direct callers:
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_init
```
**Symbols:**

```
ffffffff8151e680-ffffffff8151e702: weight_updated (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ioc_now *now</code>
</li>
</ul>
</details>
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
