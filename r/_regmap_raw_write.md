# Function: <code>_regmap_raw_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81565dc0)
Location: drivers/base/regmap/regmap.c:1198
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff81565dc0-ffffffff815664e8: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ba870)
Location: drivers/base/regmap/regmap.c:1299
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff815ba870-ffffffff815bb046: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e9c70)
Location: drivers/base/regmap/regmap.c:1346
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff815e9c70-ffffffff815ea455: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fe640)
Location: drivers/base/regmap/regmap.c:1349
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff815fe640-ffffffff815fedf0: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81666880)
Location: drivers/base/regmap/regmap.c:1428
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regmap.c:_regmap_bus_raw_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff81666880-ffffffff81667068: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a32d0)
Location: drivers/base/regmap/regmap.c:1812
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff816a32d0-ffffffff816a33f3: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3cf0)
Location: drivers/base/regmap/regmap.c:1848
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff816c3cf0-ffffffff816c3e13: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816feb90)
Location: drivers/base/regmap/regmap.c:1845
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff816feb90-ffffffff816fecae: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81722fb0)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff81722fb0-ffffffff817230ce: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817df150)
Location: drivers/base/regmap/regmap.c:1847
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff817df150-ffffffff817df2a5: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f4220)
Location: drivers/base/regmap/regmap.c:1996
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff817f4220-ffffffff817f4375: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d8a90)
Location: drivers/base/regmap/regmap.c:1996
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff817d8a90-ffffffff817d8be5: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2037
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff81d04d31-ffffffff81d04d77: _regmap_raw_write.cold (STB_LOCAL)
ffffffff818641f0-ffffffff81864365: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2056
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff81ecd769-ffffffff81ecd7bd: _regmap_raw_write.cold (STB_LOCAL)
ffffffff819ac450-ffffffff819ac5ec: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2060
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff8209944c-ffffffff820994a0: _regmap_raw_write.cold (STB_LOCAL)
ffffffff81b1fa60-ffffffff81b1fbfc: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2078
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block
```
**Symbols:**

```
ffffffff8211a4e7-ffffffff8211a53b: _regmap_raw_write.cold (STB_LOCAL)
ffffffff81b6eca0-ffffffff81b6ee3c: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len, bool noinc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1986
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block
```
**Symbols:**

```
ffffffff821f836e-ffffffff821f83c2: _regmap_raw_write.cold (STB_LOCAL)
ffffffff81bc28a0-ffffffff81bc2a3c: _regmap_raw_write (STB_GLOBAL)
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
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010917990)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffff800010917990-ffff800010917abc: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fd7f8)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
c09fd7f8-c09fd928: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009baac0)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
c0000000009baac0-c0000000009baca8: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe00059815a)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffe00059815a-ffffffe000598242: _regmap_raw_write (STB_GLOBAL)
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
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e92e0)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff816e92e0-ffffffff816e93fe: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3920)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff816c3920-ffffffff816c3a3e: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81716470)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff81716470-ffffffff8171658e: _regmap_raw_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _regmap_raw_write(struct regmap *map, unsigned int reg, const void *val, size_t val_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81731710)
Location: drivers/base/regmap/regmap.c:1852
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_write_async
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_raw_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw_flush
```
**Symbols:**

```
ffffffff81731710-ffffffff8173182e: _regmap_raw_write (STB_GLOBAL)
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
