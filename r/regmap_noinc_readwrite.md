# Function: <code>regmap_noinc_readwrite</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regmap_noinc_readwrite(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2134
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
```
**Symbols:**

```
ffffffff81b19950-ffffffff81b19abc: regmap_noinc_readwrite (STB_LOCAL)
ffffffff82098dde-ffffffff82098e41: regmap_noinc_readwrite.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regmap_noinc_readwrite(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2152
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
```
**Symbols:**

```
ffffffff81b683e0-ffffffff81b6854c: regmap_noinc_readwrite (STB_LOCAL)
ffffffff82119d3b-ffffffff82119d9e: regmap_noinc_readwrite.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regmap_noinc_readwrite(struct regmap *map, unsigned int reg, void *val, unsigned int val_len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2060
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
```
**Symbols:**

```
ffffffff81bbc0a0-ffffffff81bbc1d2: regmap_noinc_readwrite (STB_LOCAL)
ffffffff821f7be0-ffffffff821f7c43: regmap_noinc_readwrite.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
