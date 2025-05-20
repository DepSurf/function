# Function: <code>regcache_lookup_reg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81567c90)
Location: drivers/base/regmap/regcache.c:596
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff81567c90-ffffffff81567d0e: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bc830)
Location: drivers/base/regmap/regcache.c:645
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff815bc830-ffffffff815bc8b0: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815ebc40)
Location: drivers/base/regmap/regcache.c:645
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff815ebc40-ffffffff815ebcc0: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81600560)
Location: drivers/base/regmap/regcache.c:647
Inline: False
```
**Symbols:**

```
ffffffff81600560-ffffffff816005de: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816688b0)
Location: drivers/base/regmap/regcache.c:647
Inline: False
```
**Symbols:**

```
ffffffff816688b0-ffffffff8166892e: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a4230)
Location: drivers/base/regmap/regcache.c:647
Inline: False
```
**Symbols:**

```
ffffffff816a4230-ffffffff816a42ae: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4d70)
Location: drivers/base/regmap/regcache.c:647
Inline: False
```
**Symbols:**

```
ffffffff816c4d70-ffffffff816c4dee: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816ffd10)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffffffff816ffd10-ffffffff816ffd8e: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81724090)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffffffff81724090-ffffffff8172410e: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817e08a5)
Location: drivers/base/regmap/regcache.c:643
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
  - drivers/base/regmap/regcache.c:regcache_sync_block_single
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817e0af0-ffffffff817e0b6d: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817f5795)
Location: drivers/base/regmap/regcache.c:643
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
  - drivers/base/regmap/regcache.c:regcache_sync_block_single
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817f59e0-ffffffff817f5a5d: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817d957e)
Location: drivers/base/regmap/regcache.c:643
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817d9fc0-ffffffff817da03d: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff818658ab)
Location: drivers/base/regmap/regcache.c:643
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81865730-ffffffff818657ad: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff819ace94)
Location: drivers/base/regmap/regcache.c:643
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_reg_needs_sync
```
**Symbols:**

```
ffffffff819adc90-ffffffff819add1c: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81b2096f)
Location: drivers/base/regmap/regcache.c:650
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81b216c0-ffffffff81b2174c: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81b6fb52)
Location: drivers/base/regmap/regcache.c:652
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_reg_needs_sync
```
**Symbols:**

```
ffffffff81b70900-ffffffff81b7098c: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81bc37c2)
Location: drivers/base/regmap/regcache.c:689
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_reg_needs_sync
```
**Symbols:**

```
ffffffff81bc4600-ffffffff81bc468c: regcache_lookup_reg (STB_GLOBAL)
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
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff800010918c70)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffff800010918c70-ffff800010918d00: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09fe8cc)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
c09fe8cc-c09fe964: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bc520)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
c0000000009bc520-c0000000009bc5d0: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe000599042)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffffffe000599042-ffffffe00059909e: regcache_lookup_reg (STB_GLOBAL)
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
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816ea3c0)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffffffff816ea3c0-ffffffff816ea43e: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4a00)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffffffff816c4a00-ffffffff816c4a7e: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81717550)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffffffff81717550-ffffffff817175ce: regcache_lookup_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regcache_lookup_reg(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81732850)
Location: drivers/base/regmap/regcache.c:643
Inline: False
```
**Symbols:**

```
ffffffff81732850-ffffffff817328ce: regcache_lookup_reg (STB_GLOBAL)
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
