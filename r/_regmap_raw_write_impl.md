# Function: <code>_regmap_raw_write_impl</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a1a20)
Location: drivers/base/regmap/regmap.c:1443
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff816a1a20-ffffffff816a21f2: _regmap_raw_write_impl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2320)
Location: drivers/base/regmap/regmap.c:1481
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff816c2320-ffffffff816c2af2: _regmap_raw_write_impl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff816fd2a0-ffffffff816fd99a: _regmap_raw_write_impl (STB_LOCAL)
ffffffff816ff16f-ffffffff816ff204: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81721650-ffffffff81721db1: _regmap_raw_write_impl (STB_LOCAL)
ffffffff8172357a-ffffffff817235ff: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1471
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff817dd5b0-ffffffff817ddd9a: _regmap_raw_write_impl (STB_LOCAL)
ffffffff817df78d-ffffffff817df80d: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1617
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff817f2660-ffffffff817f2e11: _regmap_raw_write_impl (STB_LOCAL)
ffffffff81c0f41e-ffffffff81c0f49e: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1617
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff817d6f10-ffffffff817d7697: _regmap_raw_write_impl (STB_LOCAL)
ffffffff81c0156c-ffffffff81c015e8: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1658
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81862570-ffffffff81862d17: _regmap_raw_write_impl (STB_LOCAL)
ffffffff81d04977-ffffffff81d04ade: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1677
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff819aa530-ffffffff819aad77: _regmap_raw_write_impl (STB_LOCAL)
ffffffff81ecd323-ffffffff81ecd4a2: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1679
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81b1d870-ffffffff81b1e1c0: _regmap_raw_write_impl (STB_LOCAL)
ffffffff820990b2-ffffffff82099196: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1691
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81b6c900-ffffffff81b6d273: _regmap_raw_write_impl (STB_LOCAL)
ffffffff8211a18f-ffffffff8211a254: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1597
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81bc0530-ffffffff81bc0e8f: _regmap_raw_write_impl (STB_LOCAL)
ffffffff821f8034-ffffffff821f80db: _regmap_raw_write_impl.cold (STB_LOCAL)
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
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010915cd0)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffff800010915cd0-ffff8000109165d0: _regmap_raw_write_impl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fbc1c)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
c09fbc1c-c09fc4b0: _regmap_raw_write_impl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b8510)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
c0000000009b8510-c0000000009b8f90: _regmap_raw_write_impl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000596cea)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffe000596cea-ffffffe0005972f2: _regmap_raw_write_impl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff816e7980-ffffffff816e80e1: _regmap_raw_write_impl (STB_LOCAL)
ffffffff816e98aa-ffffffff816e992f: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff816c1fc0-ffffffff816c2721: _regmap_raw_write_impl (STB_LOCAL)
ffffffff816c3eea-ffffffff816c3f6f: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff81714b10-ffffffff81715271: _regmap_raw_write_impl (STB_LOCAL)
ffffffff81716a3a-ffffffff81716abf: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write_impl(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
**Symbols:**

```
ffffffff8172fd20-ffffffff817304cc: _regmap_raw_write_impl (STB_LOCAL)
ffffffff81731cda-ffffffff81731d5f: _regmap_raw_write_impl.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
