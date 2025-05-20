# Function: <code>regmap_raw_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81565960)
Location: drivers/base/regmap/regmap.c:2287
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff81565960-ffffffff81565ae0: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ba3d0)
Location: drivers/base/regmap/regmap.c:2387
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff815ba3d0-ffffffff815ba567: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e97d0)
Location: drivers/base/regmap/regmap.c:2425
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff815e97d0-ffffffff815e9967: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fe1a0)
Location: drivers/base/regmap/regmap.c:2430
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff815fe1a0-ffffffff815fe334: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816663c0)
Location: drivers/base/regmap/regmap.c:2509
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff816663c0-ffffffff81666563: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a2670)
Location: drivers/base/regmap/regmap.c:2491
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff816a2670-ffffffff816a28d4: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2f70)
Location: drivers/base/regmap/regmap.c:2588
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff816c2f70-ffffffff816c31dd: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fde10)
Location: drivers/base/regmap/regmap.c:2585
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff816fde10-ffffffff816fe07f: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81722230)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff81722230-ffffffff8172249f: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817de220)
Location: drivers/base/regmap/regmap.c:2587
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff817de220-ffffffff817de4be: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f3240)
Location: drivers/base/regmap/regmap.c:2744
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff817f3240-ffffffff817f34de: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d7ac0)
Location: drivers/base/regmap/regmap.c:2744
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff817d7ac0-ffffffff817d7d5c: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2785
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff81d04ade-ffffffff81d04b69: regmap_raw_read.cold (STB_LOCAL)
ffffffff81863110-ffffffff8186343b: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2805
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff81ecd4de-ffffffff81ecd577: regmap_raw_read.cold (STB_LOCAL)
ffffffff819ab200-ffffffff819ab543: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2938
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff820991d2-ffffffff8209926b: regmap_raw_read.cold (STB_LOCAL)
ffffffff81b1e680-ffffffff81b1e9c3: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2962
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff8211a254-ffffffff8211a31d: regmap_raw_read.cold (STB_LOCAL)
ffffffff81b6d8a0-ffffffff81b6dc14: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2850
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff821f80db-ffffffff821f81a4: regmap_raw_read.cold (STB_LOCAL)
ffffffff81bc14b0-ffffffff81bc1824: regmap_raw_read (STB_GLOBAL)
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
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010916b18)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffff800010916b18-ffff800010916d4c: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fca54)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
  - sound/soc/soc-ops.c:snd_soc_bytes_get
```
**Symbols:**

```
c09fca54-c09fccc0: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b9660)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
c0000000009b9660-c0000000009b9a0c: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe0005976c4)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffe0005976c4-ffffffe000597860: regmap_raw_read (STB_GLOBAL)
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
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e8560)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
```
**Symbols:**

```
ffffffff816e8560-ffffffff816e87cf: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2ba0)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
```
**Symbols:**

```
ffffffff816c2ba0-ffffffff816c2e0f: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817156f0)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff817156f0-ffffffff8171595f: regmap_raw_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regmap_raw_read(struct regmap *map, unsigned int reg, void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81730990)
Location: drivers/base/regmap/regmap.c:2592
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/mfd/88pm860x-i2c.c:pm860x_bulk_read
```
**Symbols:**

```
ffffffff81730990-ffffffff81730bff: regmap_raw_read (STB_GLOBAL)
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
