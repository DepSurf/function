# Function: <code>set_current_rng</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8151aa70)
Location: drivers/char/hw_random/core.c:107
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_register
```
**Symbols:**

```
ffffffff8151aa70-ffffffff8151abc7: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8156d7a0)
Location: drivers/char/hw_random/core.c:107
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff8156d7a0-ffffffff8156d8f7: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81599f00)
Location: drivers/char/hw_random/core.c:107
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff81599f00-ffffffff8159a05b: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff815adee0)
Location: drivers/char/hw_random/core.c:83
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff815adee0-ffffffff815ae02f: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816148e0)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff816148e0-ffffffff81614a63: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8164e500)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff8164e500-ffffffff8164e67a: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8166c790)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
```
**Symbols:**

```
ffffffff8166c790-ffffffff8166c90a: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816a2482)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff816a2380-ffffffff816a24c1: set_current_rng (STB_LOCAL)
ffffffff816a2924-ffffffff816a2947: set_current_rng.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816c5223)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff816c5120-ffffffff816c5262: set_current_rng (STB_LOCAL)
ffffffff816c56ae-ffffffff816c56d1: set_current_rng.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff817793c0)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff817793c0-ffffffff8177940c: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81793f70)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff81793f70-ffffffff81793fbc: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81776c7d)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff81776b50-ffffffff81776c86: set_current_rng (STB_LOCAL)
ffffffff81bfa7cb-ffffffff81bfa7ee: set_current_rng.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (0)
Location: drivers/char/hw_random/core.c:86
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff817fc520-ffffffff817fc656: set_current_rng (STB_LOCAL)
ffffffff81cfb25a-ffffffff81cfb27d: set_current_rng.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8193b180)
Location: drivers/char/hw_random/core.c:86
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff8193b180-ffffffff8193b25a: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81a9b840)
Location: drivers/char/hw_random/core.c:88
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff81a9b840-ffffffff81a9b981: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81ae71a0)
Location: drivers/char/hw_random/core.c:88
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff81ae71a0-ffffffff81ae72d5: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81b3a570)
Location: drivers/char/hw_random/core.c:90
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff81b3a570-ffffffff81b3a6a5: set_current_rng (STB_LOCAL)
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
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffff8000108b7178)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffff8000108b7178-ffff8000108b72b4: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (c09b0e2c)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
c09b0e2c-c09b0f78: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (c000000000951490)
Location: drivers/char/hw_random/core.c:86
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
c000000000951490-c0000000009516b8: set_current_rng (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffe000567ed6)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffe000567ed6-ffffffe000568024: set_current_rng (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8168ac73)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff8168ab70-ffffffff8168acb2: set_current_rng (STB_LOCAL)
ffffffff8168b0fe-ffffffff8168b121: set_current_rng.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81668673)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff81668570-ffffffff816686b2: set_current_rng (STB_LOCAL)
ffffffff81668afe-ffffffff81668b21: set_current_rng.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816b8ee3)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff816b8de0-ffffffff816b8f22: set_current_rng (STB_LOCAL)
ffffffff816b936e-ffffffff816b9391: set_current_rng.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int set_current_rng(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff816d34b3)
Location: drivers/char/hw_random/core.c:86
Inline: True
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:enable_best_rng
```
**Symbols:**

```
ffffffff816d33b0-ffffffff816d34f2: set_current_rng (STB_LOCAL)
ffffffff816d393e-ffffffff816d3961: set_current_rng.cold (STB_LOCAL)
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
