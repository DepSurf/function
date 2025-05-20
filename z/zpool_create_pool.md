# Function: <code>zpool_create_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81204360)
Location: mm/zpool.c:153
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81204360-ffffffff81204518: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81229300)
Location: mm/zpool.c:153
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81229300-ffffffff812294a8: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff8123b8a0)
Location: mm/zpool.c:153
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff8123b8a0-ffffffff8123ba48: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff812474f0)
Location: mm/zpool.c:153
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812474f0-ffffffff812476a5: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81267690)
Location: mm/zpool.c:153
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81267690-ffffffff8126784a: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:154
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff8128c2cf-ffffffff8128c324: zpool_create_pool.cold.5 (STB_LOCAL)
ffffffff8128bfa0-ffffffff8128c12c: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:154
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812a123f-ffffffff812a1294: zpool_create_pool.cold.5 (STB_LOCAL)
ffffffff812a0f00-ffffffff812a1093: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812bc4f2-ffffffff812bc549: zpool_create_pool.cold (STB_LOCAL)
ffffffff812bc1a0-ffffffff812bc331: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812ce3df-ffffffff812ce436: zpool_create_pool.cold (STB_LOCAL)
ffffffff812ce080-ffffffff812ce211: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff813046ff-ffffffff81304756: zpool_create_pool.cold (STB_LOCAL)
ffffffff81304390-ffffffff81304527: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81bea31b-ffffffff81bea372: zpool_create_pool.cold (STB_LOCAL)
ffffffff81310150-ffffffff813102e7: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:156
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81bdc352-ffffffff81bdc3a9: zpool_create_pool.cold (STB_LOCAL)
ffffffff81316210-ffffffff813163ae: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:156
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81cc3406-ffffffff81cc3476: zpool_create_pool.cold (STB_LOCAL)
ffffffff81362330-ffffffff81362523: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:151
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81e75a6d-ffffffff81e75ad3: zpool_create_pool.cold (STB_LOCAL)
ffffffff813dee20-ffffffff813defd7: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff81465b40)
Location: mm/zpool.c:148
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff81465b40-ffffffff81465d0a: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff8149b5c0)
Location: mm/zpool.c:147
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff8149b5c0-ffffffff8149b77e: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffff814caca0)
Location: mm/zpool.c:147
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff814caca0-ffffffff814cae79: zpool_create_pool (STB_GLOBAL)
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
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffff800010372700)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffff800010372700-ffff800010372930: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c055f278)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
c055f278-c055f454: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (c0000000004642e0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
c0000000004642e0-c00000000046457c: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zpool.c (ffffffe00024b858)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffe00024b858-ffffffe00024ba66: zpool_create_pool (STB_GLOBAL)
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
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812c69bf-ffffffff812c6a16: zpool_create_pool.cold (STB_LOCAL)
ffffffff812c6660-ffffffff812c67f1: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812b79ff-ffffffff812b7a56: zpool_create_pool.cold (STB_LOCAL)
ffffffff812b76a0-ffffffff812b7831: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812c47cf-ffffffff812c4826: zpool_create_pool.cold (STB_LOCAL)
ffffffff812c4470-ffffffff812c4601: zpool_create_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct zpool *zpool_create_pool(const char *type, const char *name, gfp_t gfp, const struct zpool_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zpool.c (0)
Location: mm/zpool.c:155
Inline: False
Direct callers:
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff812d525f-ffffffff812d52b6: zpool_create_pool.cold (STB_LOCAL)
ffffffff812d4f10-ffffffff812d509f: zpool_create_pool (STB_GLOBAL)
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
<code>const struct zpool_ops *ops</code>
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
