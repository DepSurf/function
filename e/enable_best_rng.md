# Function: <code>enable_best_rng</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81614a70)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff81614a70-ffffffff81614ad7: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8164e680)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff8164e680-ffffffff8164e6e7: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8166c910)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff8166c910-ffffffff8166c977: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816a24d0)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff816a24d0-ffffffff816a2537: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816c5270)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff816c5270-ffffffff816c52d8: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81779410)
Location: drivers/char/hw_random/core.c:299
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff81779410-ffffffff81779478: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81793fc0)
Location: drivers/char/hw_random/core.c:299
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff81793fc0-ffffffff81794028: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81776c90)
Location: drivers/char/hw_random/core.c:299
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff81776c90-ffffffff81776cf8: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff817fc660)
Location: drivers/char/hw_random/core.c:299
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_current_store
```
**Symbols:**

```
ffffffff817fc660-ffffffff817fc6c8: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8193b260)
Location: drivers/char/hw_random/core.c:298
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_current_store
```
**Symbols:**

```
ffffffff8193b260-ffffffff8193b30d: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81a9b9a0)
Location: drivers/char/hw_random/core.c:304
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_current_store
```
**Symbols:**

```
ffffffff81a9b9a0-ffffffff81a9ba4d: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81ae72f0)
Location: drivers/char/hw_random/core.c:304
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_current_store
```
**Symbols:**

```
ffffffff81ae72f0-ffffffff81ae73a2: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81b3a6c0)
Location: drivers/char/hw_random/core.c:311
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_store
  - drivers/char/hw_random/core.c:rng_current_store
```
**Symbols:**

```
ffffffff81b3a6c0-ffffffff81b3a772: enable_best_rng (STB_LOCAL)
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
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffff8000108b72b8)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffff8000108b72b8-ffff8000108b734c: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (c09b0f78)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
c09b0f78-c09b1008: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (c0000000009516c0)
Location: drivers/char/hw_random/core.c:295
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
c0000000009516c0-c000000000951768: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffe000568024)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffe000568024-ffffffe000568096: enable_best_rng (STB_LOCAL)
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
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8168acc0)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff8168acc0-ffffffff8168ad28: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816686c0)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff816686c0-ffffffff81668728: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816b8f30)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff816b8f30-ffffffff816b8f98: enable_best_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int enable_best_rng();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816d3500)
Location: drivers/char/hw_random/core.c:295
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff816d3500-ffffffff816d3568: enable_best_rng (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
