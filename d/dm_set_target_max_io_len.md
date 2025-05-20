# Function: <code>dm_set_target_max_io_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1630)
Location: drivers/md/dm.c:1416
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff816a1630-ffffffff816a166c: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702680)
Location: drivers/md/dm.c:893
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81702680-ffffffff817026bc: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81734540)
Location: drivers/md/dm.c:893
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81734540-ffffffff8173457c: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174d900)
Location: drivers/md/dm.c:906
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff8174d900-ffffffff8174d93c: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bf9f0)
Location: drivers/md/dm.c:915
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff817bf9f0-ffffffff817bfa2c: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:999
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff8180a9a9-ffffffff8180a9cd: dm_set_target_max_io_len.cold.53 (STB_LOCAL)
ffffffff81807c30-ffffffff81807c5e: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff818369ac)
Location: drivers/md/dm.c:1054
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff818369a9-ffffffff818369cd: dm_set_target_max_io_len.cold.57 (STB_LOCAL)
ffffffff81833b00-ffffffff81833b2e: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81879542)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81879542-ffffffff81879563: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff818758f0-ffffffff81875913: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff818ab382)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff818ab382-ffffffff818ab3a3: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff818a76e0-ffffffff818a7703: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff8197b56d)
Location: drivers/md/dm.c:1074
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff8197b56d-ffffffff8197b58e: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff819773e0-ffffffff81977406: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81c28058)
Location: drivers/md/dm.c:1079
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81c28058-ffffffff81c28079: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff8197c060-ffffffff8197c086: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81c1a1e6)
Location: drivers/md/dm.c:1083
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81c1a1e6-ffffffff81c1a207: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff8195ffc0-ffffffff8195ffe5: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81d29eca)
Location: drivers/md/dm.c:970
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81d29eca-ffffffff81d29eeb: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff81a07f90-ffffffff81a07fb5: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81ef61bd)
Location: drivers/md/dm.c:1107
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81ef61bd-ffffffff81ef61de: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff81b704b0-ffffffff81b704df: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0d030)
Location: drivers/md/dm.c:1180
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81d0d030-ffffffff81d0d07b: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d75df0)
Location: drivers/md/dm.c:1204
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81d75df0-ffffffff81d75e3b: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2d020)
Location: drivers/md/dm.c:1190
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81e2d020-ffffffff81e2d06b: dm_set_target_max_io_len (STB_GLOBAL)
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
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afc588)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffff800010afc588-ffff800010afc5ec: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd3c4)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
c0bdd3c4-c0bdd42c: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bebd70)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
c000000000bebd70-c000000000bebde8: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006eddd6)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffe0006eddd6-ffffffe0006ede2e: dm_set_target_max_io_len (STB_GLOBAL)
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
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81851202)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81851202-ffffffff81851223: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff8184d560-ffffffff8184d583: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff81818812)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff81818812-ffffffff81818833: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff81814b80-ffffffff81814ba3: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff818a0832)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff818a0832-ffffffff818a0853: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff8189cb90-ffffffff8189cbb3: dm_set_target_max_io_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dm_set_target_max_io_len(struct dm_target *ti, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff818bca72)
Location: drivers/md/dm.c:1048
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
**Symbols:**

```
ffffffff818bca72-ffffffff818bca93: dm_set_target_max_io_len.cold (STB_LOCAL)
ffffffff818b8ef0-ffffffff818b8f13: dm_set_target_max_io_len (STB_GLOBAL)
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
