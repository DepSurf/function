# Function: <code>__zswap_pool_current</code>

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
In mm/zswap.c (ffffffff811d81f6)
Location: mm/zswap.c:496
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
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
In mm/zswap.c (ffffffff811f6b36)
Location: mm/zswap.c:498
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
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
In mm/zswap.c (ffffffff812074ea)
Location: mm/zswap.c:422
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81212150)
Location: mm/zswap.c:426
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
**Symbols:**

```
ffffffff81212150-ffffffff812121aa: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8122cb20)
Location: mm/zswap.c:426
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff8122cb20-ffffffff8122cba9: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8124f7a0)
Location: mm/zswap.c:441
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff8124f7a0-ffffffff8124f829: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81263e90)
Location: mm/zswap.c:441
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81263e90-ffffffff81263f19: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8127ee00)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff8127ee00-ffffffff8127ee89: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8128e850)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff8128e850-ffffffff8128e8d9: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812c1150)
Location: mm/zswap.c:449
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff812c1150-ffffffff812c11d7: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812ccc70)
Location: mm/zswap.c:503
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff812ccc70-ffffffff812cccf7: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812d3840)
Location: mm/zswap.c:503
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff812d3840-ffffffff812d389f: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zswap.c (ffffffff813194c5)
Location: mm/zswap.c:503
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff81319490-ffffffff81319501: __zswap_pool_current (STB_LOCAL)
ffffffff81cbeef1-ffffffff81cbef19: __zswap_pool_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:518
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff813846e0-ffffffff8138476e: __zswap_pool_current (STB_LOCAL)
ffffffff81e710ce-ffffffff81e710f6: __zswap_pool_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:518
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff814022e0-ffffffff8140236e: __zswap_pool_current (STB_LOCAL)
ffffffff82065e71-ffffffff82065e99: __zswap_pool_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zswap.c (ffffffff81436cb0)
Location: mm/zswap.c:532
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff814351c0-ffffffff81435222: __zswap_pool_current.part.0 (STB_LOCAL)
ffffffff820e5615-ffffffff820e563d: __zswap_pool_current.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zswap.c (ffffffff8146fc21)
Location: mm/zswap.c:766
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
  - mm/zswap.c:zswap_pool_current_get
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
  - mm/zswap.c:zswap_pool_current_get
```
**Symbols:**

```
ffffffff8146e260-ffffffff8146e2c2: __zswap_pool_current.part.0 (STB_LOCAL)
ffffffff821c27a3-ffffffff821c27cb: __zswap_pool_current.part.0.cold (STB_LOCAL)
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
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffff80001032b0d8)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
**Symbols:**

```
ffff80001032b0d8-ffff80001032b188: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (c0541814)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
**Symbols:**

```
c0541814-c05418ec: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (c000000000402140)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_pool_current
```
**Symbols:**

```
c000000000402140-c000000000402220: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffe00022a12c)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffe00022a12c-ffffffe00022a1a2: __zswap_pool_current (STB_LOCAL)
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
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81286e30)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff81286e30-ffffffff81286eb9: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81278c90)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff81278c90-ffffffff81278d19: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81284c40)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff81284c40-ffffffff81284cc9: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct zswap_pool *__zswap_pool_current();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812948e0)
Location: mm/zswap.c:432
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
**Symbols:**

```
ffffffff812948e0-ffffffff81294969: __zswap_pool_current (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
