# Function: <code>_regmap_raw_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81565720)
Location: drivers/base/regmap/regmap.c:2153
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_bus_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff81565720-ffffffff815658f2: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ba190)
Location: drivers/base/regmap/regmap.c:2250
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff815ba190-ffffffff815ba369: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e9580)
Location: drivers/base/regmap/regmap.c:2296
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff815e9580-ffffffff815e9769: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fdf60)
Location: drivers/base/regmap/regmap.c:2301
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff815fdf60-ffffffff815fe139: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81666170)
Location: drivers/base/regmap/regmap.c:2380
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff81666170-ffffffff81666358: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a23f0)
Location: drivers/base/regmap/regmap.c:2360
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff816a23f0-ffffffff816a25f9: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2cf0)
Location: drivers/base/regmap/regmap.c:2459
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff816c2cf0-ffffffff816c2ef9: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2456
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff816fdba0-ffffffff816fdd98: _regmap_raw_read (STB_LOCAL)
ffffffff816ff238-ffffffff816ff261: _regmap_raw_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81721fb0)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff81721fb0-ffffffff817221b5: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817ddf90)
Location: drivers/base/regmap/regmap.c:2458
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff817ddf90-ffffffff817de1a2: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f2fe0)
Location: drivers/base/regmap/regmap.c:2615
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff817f2fe0-ffffffff817f31ca: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d7860)
Location: drivers/base/regmap/regmap.c:2615
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff817d7860-ffffffff817d7a46: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81862ee0)
Location: drivers/base/regmap/regmap.c:2656
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff81862ee0-ffffffff81863094: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2676
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff819aaf90-ffffffff819ab17e: _regmap_raw_read (STB_LOCAL)
ffffffff81ecd4c0-ffffffff81ecd4de: _regmap_raw_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2807
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff81b1e3f0-ffffffff81b1e5d7: _regmap_raw_read (STB_LOCAL)
ffffffff820991b4-ffffffff820991d2: _regmap_raw_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6d610)
Location: drivers/base/regmap/regmap.c:2824
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff81b6d610-ffffffff81b6d7f3: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bc1220)
Location: drivers/base/regmap/regmap.c:2712
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff81bc1220-ffffffff81bc1403: _regmap_raw_read (STB_LOCAL)
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
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010916848)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffff800010916848-ffff800010916a90: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fc740)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
c09fc740-c09fc9e4: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b92a0)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
c0000000009b92a0-c0000000009b957c: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe0005974a2)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffe0005974a2-ffffffe000597660: _regmap_raw_read (STB_LOCAL)
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
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e82e0)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff816e82e0-ffffffff816e84e5: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2920)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff816c2920-ffffffff816c2b25: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81715470)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff81715470-ffffffff81715675: _regmap_raw_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _regmap_raw_read(struct regmap *map, unsigned int reg, void *val, unsigned int val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817306e0)
Location: drivers/base/regmap/regmap.c:2463
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_bus_read
```
**Symbols:**

```
ffffffff817306e0-ffffffff81730917: _regmap_raw_read (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool noinc</code>
</li>
</ul>
</details>
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
