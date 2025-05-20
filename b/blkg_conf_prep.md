# Function: <code>blkg_conf_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d8f50)
Location: block/blk-cgroup.c:785
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_conf
  - block/blk-throttle.c:tg_set_max
  - block/cfq-iosched.c:__cfqg_set_weight_device
```
**Symbols:**

```
ffffffff813d8f50-ffffffff813d90e1: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141ecb0)
Location: block/blk-cgroup.c:785
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_max
```
**Symbols:**

```
ffffffff8141ecb0-ffffffff8141ee6e: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8143a270)
Location: block/blk-cgroup.c:786
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_max
```
**Symbols:**

```
ffffffff8143a270-ffffffff8143a429: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814478c0)
Location: block/blk-cgroup.c:808
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
```
**Symbols:**

```
ffffffff814478c0-ffffffff81447ba2: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814744c0)
Location: block/blk-cgroup.c:808
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
```
**Symbols:**

```
ffffffff814744c0-ffffffff814747a2: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a8600)
Location: block/blk-cgroup.c:819
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
```
**Symbols:**

```
ffffffff814a8600-ffffffff814a88aa: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c2c30)
Location: block/blk-cgroup.c:804
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
```
**Symbols:**

```
ffffffff814c2c30-ffffffff814c2f8c: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1340)
Location: block/blk-cgroup.c:768
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
```
**Symbols:**

```
ffffffff814f1340-ffffffff814f15dd: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8150aa00)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff8150aa00-ffffffff8150ac0e: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156b970)
Location: block/blk-cgroup.c:627
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff8156b970-ffffffff8156bc5d: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815865f0)
Location: block/blk-cgroup.c:608
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff815865f0-ffffffff81586925: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158d300)
Location: block/blk-cgroup.c:606
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff8158d300-ffffffff8158d635: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f2d60)
Location: block/blk-cgroup.c:621
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff815f2d60-ffffffff815f30b5: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a4090)
Location: block/blk-cgroup.c:682
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff816a4090-ffffffff816a455a: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81762e20)
Location: block/blk-cgroup.c:678
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff81762e20-ffffffff81763252: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a19b0)
Location: block/blk-cgroup.c:799
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff817a19b0-ffffffff817a1d7c: blkg_conf_prep.part.0 (STB_LOCAL)
ffffffff817a2360-ffffffff817a23a2: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e5500)
Location: block/blk-cgroup.c:812
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff817e5500-ffffffff817e58c9: blkg_conf_prep.part.0 (STB_LOCAL)
ffffffff817e5ea0-ffffffff817e5ee2: blkg_conf_prep (STB_GLOBAL)
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
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060e038)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffff80001060e038-ffff80001060e350: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b8aa0)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
c07b8aa0-c07b8ccc: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007ab390)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
c0000000007ab390-c0000000007ab790: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe00044664a)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffe00044664a-ffffffe00044689e: blkg_conf_prep (STB_GLOBAL)
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
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81502fe0)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff81502fe0-ffffffff815031ee: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f34c0)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff814f34c0-ffffffff814f36c2: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814ff070)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff814ff070-ffffffff814ff27e: blkg_conf_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkg_conf_prep(struct blkcg *blkcg, const struct blkcg_policy *pol, char *input, struct blkg_conf_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815181f0)
Location: block/blk-cgroup.c:806
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-iocost.c:ioc_weight_write
```
**Symbols:**

```
ffffffff815181f0-ffffffff815183ed: blkg_conf_prep (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>char *input</code>
</li>
<li>
<b>Param reordered. </b>
<code>blkcg, pol, input, ctx</code> ➡️ <code>blkcg, pol, ctx</code>
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
