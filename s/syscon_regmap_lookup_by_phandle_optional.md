# Function: <code>syscon_regmap_lookup_by_phandle_optional</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct regmap *syscon_regmap_lookup_by_phandle_optional(struct device_node *np, const char *property);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8181c8d0)
Location: drivers/mfd/syscon.c:263
Inline: False
```
**Symbols:**

```
ffffffff8181c8d0-ffffffff8181c8f0: syscon_regmap_lookup_by_phandle_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct regmap *syscon_regmap_lookup_by_phandle_optional(struct device_node *np, const char *property);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff817ffca0)
Location: drivers/mfd/syscon.c:263
Inline: False
```
**Symbols:**

```
ffffffff817ffca0-ffffffff817ffcc0: syscon_regmap_lookup_by_phandle_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct regmap *syscon_regmap_lookup_by_phandle_optional(struct device_node *np, const char *property);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8188a0a0)
Location: drivers/mfd/syscon.c:263
Inline: False
```
**Symbols:**

```
ffffffff8188a0a0-ffffffff8188a0c0: syscon_regmap_lookup_by_phandle_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct regmap *syscon_regmap_lookup_by_phandle_optional(struct device_node *np, const char *property);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff819d3370)
Location: drivers/mfd/syscon.c:263
Inline: False
```
**Symbols:**

```
ffffffff819d3370-ffffffff819d33a0: syscon_regmap_lookup_by_phandle_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regmap *syscon_regmap_lookup_by_phandle_optional(struct device_node *np, const char *property);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81b4d7e0)
Location: drivers/mfd/syscon.c:262
Inline: False
```
**Symbols:**

```
ffffffff81b4d7e0-ffffffff81b4d810: syscon_regmap_lookup_by_phandle_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regmap *syscon_regmap_lookup_by_phandle_optional(struct device_node *np, const char *property);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81ba0c50)
Location: drivers/mfd/syscon.c:277
Inline: False
```
**Symbols:**

```
ffffffff81ba0c50-ffffffff81ba0c80: syscon_regmap_lookup_by_phandle_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regmap *syscon_regmap_lookup_by_phandle_optional(struct device_node *np, const char *property);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81bf4db0)
Location: drivers/mfd/syscon.c:281
Inline: False
```
**Symbols:**

```
ffffffff81bf4db0-ffffffff81bf4de0: syscon_regmap_lookup_by_phandle_optional (STB_GLOBAL)
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
