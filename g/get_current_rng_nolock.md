# Function: <code>get_current_rng_nolock</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81779eb5)
Location: drivers/char/hw_random/core.c:114
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct hwrng *get_current_rng_nolock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81794070)
Location: drivers/char/hw_random/core.c:114
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
**Symbols:**

```
ffffffff81793ad0-ffffffff81793b27: get_current_rng_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct hwrng *get_current_rng_nolock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81776d40)
Location: drivers/char/hw_random/core.c:114
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
**Symbols:**

```
ffffffff817766b0-ffffffff81776707: get_current_rng_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct hwrng *get_current_rng_nolock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff817fcad0)
Location: drivers/char/hw_random/core.c:114
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
**Symbols:**

```
ffffffff817fc440-ffffffff817fc497: get_current_rng_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct hwrng *get_current_rng_nolock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8193b912)
Location: drivers/char/hw_random/core.c:114
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
**Symbols:**

```
ffffffff8193b070-ffffffff8193b0e5: get_current_rng_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct hwrng *get_current_rng_nolock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81a9c0b8)
Location: drivers/char/hw_random/core.c:125
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
**Symbols:**

```
ffffffff81a9b710-ffffffff81a9b785: get_current_rng_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct hwrng *get_current_rng_nolock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81ae7a18)
Location: drivers/char/hw_random/core.c:125
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
**Symbols:**

```
ffffffff81ae7070-ffffffff81ae70e5: get_current_rng_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct hwrng *get_current_rng_nolock();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81b3ae88)
Location: drivers/char/hw_random/core.c:127
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:rng_quality_show
  - drivers/char/hw_random/core.c:rng_current_show
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
**Symbols:**

```
ffffffff81b3a440-ffffffff81b3a4b5: get_current_rng_nolock (STB_LOCAL)
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
