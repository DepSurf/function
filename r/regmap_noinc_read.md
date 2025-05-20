# Function: <code>regmap_noinc_read</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c33e0)
Location: drivers/base/regmap/regmap.c:2684
Inline: False
```
**Symbols:**

```
ffffffff816c33e0-ffffffff816c34f4: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fe280)
Location: drivers/base/regmap/regmap.c:2681
Inline: False
```
**Symbols:**

```
ffffffff816fe280-ffffffff816fe3af: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817226a0)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
ffffffff817226a0-ffffffff817227cf: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817de6f0)
Location: drivers/base/regmap/regmap.c:2683
Inline: False
```
**Symbols:**

```
ffffffff817de6f0-ffffffff817de845: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f3710)
Location: drivers/base/regmap/regmap.c:2840
Inline: False
```
**Symbols:**

```
ffffffff817f3710-ffffffff817f3865: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d7f90)
Location: drivers/base/regmap/regmap.c:2840
Inline: False
```
**Symbols:**

```
ffffffff817d7f90-ffffffff817d80e4: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81863690)
Location: drivers/base/regmap/regmap.c:2881
Inline: False
```
**Symbols:**

```
ffffffff81863690-ffffffff818637e4: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819ab7f0)
Location: drivers/base/regmap/regmap.c:2899
Inline: False
```
**Symbols:**

```
ffffffff819ab7f0-ffffffff819ab934: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3032
Inline: False
```
**Symbols:**

```
ffffffff820992ac-ffffffff820992c1: regmap_noinc_read.cold (STB_LOCAL)
ffffffff81b1ed00-ffffffff81b1ee95: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3061
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff8211a35e-ffffffff8211a388: regmap_noinc_read.cold (STB_LOCAL)
ffffffff81b6df00-ffffffff81b6e0b6: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2949
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
**Symbols:**

```
ffffffff821f81e5-ffffffff821f820f: regmap_noinc_read.cold (STB_LOCAL)
ffffffff81bc1b00-ffffffff81bc1cb6: regmap_noinc_read (STB_GLOBAL)
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
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010916f70)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
ffff800010916f70-ffff80001091709c: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fce6c)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
c09fce6c-c09fcf88: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b9cd0)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
c0000000009b9cd0-c0000000009b9e7c: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe0005979e6)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
ffffffe0005979e6-ffffffe000597ab8: regmap_noinc_read (STB_GLOBAL)
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
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e89d0)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
ffffffff816e89d0-ffffffff816e8aff: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3010)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
ffffffff816c3010-ffffffff816c313f: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81715b60)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
ffffffff81715b60-ffffffff81715c8f: regmap_noinc_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_noinc_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81730e00)
Location: drivers/base/regmap/regmap.c:2688
Inline: False
```
**Symbols:**

```
ffffffff81730e00-ffffffff81730f2f: regmap_noinc_read (STB_GLOBAL)
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
