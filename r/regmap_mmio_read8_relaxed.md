# Function: <code>regmap_mmio_read8_relaxed</code>

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
unsigned int regmap_mmio_read8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f83b0)
Location: drivers/base/regmap/regmap-mmio.c:169
Inline: False
```
**Symbols:**

```
ffffffff817f83b0-ffffffff817f83c5: regmap_mmio_read8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int regmap_mmio_read8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcb40)
Location: drivers/base/regmap/regmap-mmio.c:169
Inline: False
```
**Symbols:**

```
ffffffff817dcb40-ffffffff817dcb55: regmap_mmio_read8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int regmap_mmio_read8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81868540)
Location: drivers/base/regmap/regmap-mmio.c:169
Inline: False
```
**Symbols:**

```
ffffffff81868540-ffffffff81868555: regmap_mmio_read8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int regmap_mmio_read8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0f80)
Location: drivers/base/regmap/regmap-mmio.c:169
Inline: False
```
**Symbols:**

```
ffffffff819b0f80-ffffffff819b0f9d: regmap_mmio_read8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int regmap_mmio_read8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b24f00)
Location: drivers/base/regmap/regmap-mmio.c:253
Inline: False
```
**Symbols:**

```
ffffffff81b24f00-ffffffff81b24f1d: regmap_mmio_read8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int regmap_mmio_read8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b75000)
Location: drivers/base/regmap/regmap-mmio.c:253
Inline: False
```
**Symbols:**

```
ffffffff81b75000-ffffffff81b7501d: regmap_mmio_read8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int regmap_mmio_read8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc8e80)
Location: drivers/base/regmap/regmap-mmio.c:239
Inline: False
```
**Symbols:**

```
ffffffff81bc8e80-ffffffff81bc8e9d: regmap_mmio_read8_relaxed (STB_LOCAL)
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
