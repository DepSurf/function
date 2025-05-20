# Function: <code>add_hwgenerator_randomness</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81512c40)
Location: drivers/char/random.c:1844
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81512c40-ffffffff81512d32: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81567820)
Location: drivers/char/random.c:2126
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81567820-ffffffff8156792e: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81593f50)
Location: drivers/char/random.c:2140
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81593f50-ffffffff8159405e: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7cd0)
Location: drivers/char/random.c:2213
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff815a7cd0-ffffffff815a7dde: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160e5d0)
Location: drivers/char/random.c:2212
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff8160e5d0-ffffffff8160e6de: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81647f20)
Location: drivers/char/random.c:2320
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81647f20-ffffffff8164802e: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816663c0)
Location: drivers/char/random.c:2345
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff816663c0-ffffffff816664ce: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169c0b0)
Location: drivers/char/random.c:2428
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff8169c0b0-ffffffff8169c1b7: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bee00)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff816bee00-ffffffff816bef07: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817727f0)
Location: drivers/char/random.c:2297
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff817727f0-ffffffff817728e9: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178d840)
Location: drivers/char/random.c:2296
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff8178d840-ffffffff8178d939: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817711b0)
Location: drivers/char/random.c:2272
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff817711b0-ffffffff817712a8: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f6d30)
Location: drivers/char/random.c:2297
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff817f6d30-ffffffff817f6e56: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void add_hwgenerator_randomness(const void *buf, size_t len, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:846
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81ec3068-ffffffff81ec3075: add_hwgenerator_randomness.cold (STB_LOCAL)
ffffffff81934b40-ffffffff81934be1: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void add_hwgenerator_randomness(const void *buf, size_t len, size_t entropy, bool sleep_after);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:934
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:add_early_randomness
```
**Symbols:**

```
ffffffff82096502-ffffffff82096516: add_hwgenerator_randomness.cold (STB_LOCAL)
ffffffff81a94a50-ffffffff81a94b53: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void add_hwgenerator_randomness(const void *buf, size_t len, size_t entropy, bool sleep_after);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:934
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:add_early_randomness
```
**Symbols:**

```
ffffffff8211744a-ffffffff8211745e: add_hwgenerator_randomness.cold (STB_LOCAL)
ffffffff81ae0270-ffffffff81ae0373: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void add_hwgenerator_randomness(const void *buf, size_t len, size_t entropy, bool sleep_after);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:934
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:add_early_randomness
```
**Symbols:**

```
ffffffff821f51bf-ffffffff821f51d3: add_hwgenerator_randomness.cold (STB_LOCAL)
ffffffff81b33670-ffffffff81b33773: add_hwgenerator_randomness (STB_GLOBAL)
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
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b08d8)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffff8000108b08d8-ffff8000108b0a14: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09ab52c)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
c09ab52c-c09ab64c: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947a80)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
c000000000947a80-c000000000947c3c: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000563762)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffe000563762-ffffffe000563876: add_hwgenerator_randomness (STB_GLOBAL)
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
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81684870)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81684870-ffffffff81684977: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816624f0)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff816624f0-ffffffff816625f7: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b2c40)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff816b2c40-ffffffff816b2d47: add_hwgenerator_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_hwgenerator_randomness(const char *buffer, size_t count, size_t entropy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd1a0)
Location: drivers/char/random.c:2489
Inline: False
Direct callers:
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff816cd1a0-ffffffff816cd2a2: add_hwgenerator_randomness (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *buf</code>
</li>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool sleep_after</code>
</li>
</ul>
</details>
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
