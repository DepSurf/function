# Function: <code>extract_entropy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t extract_entropy(struct entropy_store *r, void *buf, size_t nbytes, int min, int reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81513040)
Location: drivers/char/random.c:1153
Inline: False
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes_arch
```
**Symbols:**

```
ffffffff81513040-ffffffff81513221: extract_entropy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t extract_entropy(struct entropy_store *r, void *buf, size_t nbytes, int min, int reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81566f70)
Location: drivers/char/random.c:1423
Inline: False
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81566f70-ffffffff8156704b: extract_entropy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t extract_entropy(struct entropy_store *r, void *buf, size_t nbytes, int min, int reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815936d0)
Location: drivers/char/random.c:1423
Inline: False
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff815936d0-ffffffff815937ab: extract_entropy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff815a7860)
Location: drivers/char/random.c:1403
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff815a7860-ffffffff815a791e: extract_entropy.constprop.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8160e160)
Location: drivers/char/random.c:1402
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8160e160-ffffffff8160e220: extract_entropy.constprop.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81647c20)
Location: drivers/char/random.c:1506
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81647c20-ffffffff81647ce1: extract_entropy.constprop.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816660c0)
Location: drivers/char/random.c:1515
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816660c0-ffffffff81666181: extract_entropy.constprop.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8169bb70)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8169bb70-ffffffff8169bc4e: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816be8a0)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816be8a0-ffffffff816be97e: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff817721d0)
Location: drivers/char/random.c:1487
Inline: True
Direct callers:
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff817721d0-ffffffff8177226f: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8178d260)
Location: drivers/char/random.c:1486
Inline: True
Direct callers:
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff8178d260-ffffffff8178d2d1: extract_entropy.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81770260)
Location: drivers/char/random.c:1462
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
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
In drivers/char/random.c (ffffffff817f5c44)
Location: drivers/char/random.c:1482
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff819343a0)
Location: drivers/char/random.c:591
Inline: True
Direct callers:
  - drivers/char/random.c:_credit_init_bits
  - drivers/char/random.c:crng_make_state
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff819343a0-ffffffff819346b9: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81a930f0)
Location: drivers/char/random.c:651
Inline: True
Direct callers:
  - drivers/char/random.c:crng_make_state
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81a930f0-ffffffff81a93406: extract_entropy.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81adeb20)
Location: drivers/char/random.c:651
Inline: True
Direct callers:
  - drivers/char/random.c:crng_make_state
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81adeb20-ffffffff81aded87: extract_entropy.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81b31f40)
Location: drivers/char/random.c:651
Inline: True
Direct callers:
  - drivers/char/random.c:crng_make_state
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81b31f40-ffffffff81b321a7: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffff8000108af618)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffff8000108af618-ffff8000108af720: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (c09a9f8c)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
```
**Symbols:**

```
c09a9f8c-c09aa0a4: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (c000000000946a20)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
c000000000946a20-c000000000946b60: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffe000562f64)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
```
**Symbols:**

```
ffffffe000562f64-ffffffe00056303e: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81684310)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81684310-ffffffff816843ee: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81661f90)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81661f90-ffffffff8166206e: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816b26e0)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816b26e0-ffffffff816b27be: extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816ccbe0)
Location: drivers/char/random.c:1592
Inline: True
Direct callers:
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff816ccbe0-ffffffff816cccd7: extract_entropy.constprop.0 (STB_LOCAL)
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
</ul>
