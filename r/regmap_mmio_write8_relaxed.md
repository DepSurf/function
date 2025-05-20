# Function: <code>regmap_mmio_write8_relaxed</code>

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
void regmap_mmio_write8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f82b0)
Location: drivers/base/regmap/regmap-mmio.c:79
Inline: False
```
**Symbols:**

```
ffffffff817f82b0-ffffffff817f82c2: regmap_mmio_write8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void regmap_mmio_write8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dca40)
Location: drivers/base/regmap/regmap-mmio.c:79
Inline: False
```
**Symbols:**

```
ffffffff817dca40-ffffffff817dca52: regmap_mmio_write8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void regmap_mmio_write8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81868440)
Location: drivers/base/regmap/regmap-mmio.c:79
Inline: False
```
**Symbols:**

```
ffffffff81868440-ffffffff81868452: regmap_mmio_write8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void regmap_mmio_write8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0e80)
Location: drivers/base/regmap/regmap-mmio.c:79
Inline: False
```
**Symbols:**

```
ffffffff819b0e80-ffffffff819b0e9c: regmap_mmio_write8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void regmap_mmio_write8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b24de0)
Location: drivers/base/regmap/regmap-mmio.c:72
Inline: False
```
**Symbols:**

```
ffffffff81b24de0-ffffffff81b24dfc: regmap_mmio_write8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void regmap_mmio_write8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b74ee0)
Location: drivers/base/regmap/regmap-mmio.c:72
Inline: False
```
**Symbols:**

```
ffffffff81b74ee0-ffffffff81b74efc: regmap_mmio_write8_relaxed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void regmap_mmio_write8_relaxed(struct regmap_mmio_context *ctx, unsigned int reg, unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc8d60)
Location: drivers/base/regmap/regmap-mmio.c:72
Inline: False
```
**Symbols:**

```
ffffffff81bc8d60-ffffffff81bc8d7c: regmap_mmio_write8_relaxed (STB_LOCAL)
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
