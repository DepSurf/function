# Function: <code>regmap_writeable_noinc</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1ff0)
Location: drivers/base/regmap/regmap.c:181
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
```
**Symbols:**

```
ffffffff816c1ff0-ffffffff816c2028: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fcf70)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
```
**Symbols:**

```
ffffffff816fcf70-ffffffff816fcfa8: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81721320)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81721320-ffffffff81721358: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817df58a)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff817dd280-ffffffff817dd2b8: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f465a)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff817f2320-ffffffff817f2358: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d8eca)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff817d6bd0-ffffffff817d6c08: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8186465a)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81862200-ffffffff81862238: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819ac91e)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff819aa140-ffffffff819aa18c: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1ffff)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81b1d420-ffffffff81b1d46c: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6f24f)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81b6c490-ffffffff81b6c4dc: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bc2e1f)
Location: drivers/base/regmap/regmap.c:178
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81bc00c0-ffffffff81bc010c: regmap_writeable_noinc (STB_GLOBAL)
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
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff8000109158c8)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffff8000109158c8-ffff800010915930: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fb844)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
c09fb844-c09fb88c: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b7f70)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
c0000000009b7f70-c0000000009b7fe4: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe0005969f6)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffe0005969f6-ffffffe000596a48: regmap_writeable_noinc (STB_GLOBAL)
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
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e7650)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff816e7650-ffffffff816e7688: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1c90)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff816c1c90-ffffffff816c1cc8: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817147e0)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff817147e0-ffffffff81714818: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool regmap_writeable_noinc(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172f9e0)
Location: drivers/base/regmap/regmap.c:177
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff8172f9e0-ffffffff8172fa18: regmap_writeable_noinc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
