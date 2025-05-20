# Function: <code>icst_clk_setup</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk *icst_clk_setup(struct device *dev, const struct clk_icst_desc *desc, const char *name, const char *parent_name, struct regmap *map, enum icst_control_type ctype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/versatile/clk-icst.c (ffffffff8177f3b0)
Location: drivers/clk/versatile/clk-icst.c:336
Inline: False
Direct callers:
  - drivers/clk/versatile/clk-icst.c:icst_clk_register
```
**Symbols:**

```
ffffffff8177f3b0-ffffffff8177f4e5: icst_clk_setup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *icst_clk_setup(struct device *dev, const struct clk_icst_desc *desc, const char *name, const char *parent_name, struct regmap *map, enum icst_control_type ctype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/versatile/clk-icst.c (c091ce78)
Location: drivers/clk/versatile/clk-icst.c:347
Inline: False
Direct callers:
  - drivers/clk/versatile/clk-icst.c:of_syscon_icst_setup
  - drivers/clk/versatile/clk-icst.c:icst_clk_register
```
**Symbols:**

```
c091ce78-c091cfbc: icst_clk_setup (STB_LOCAL)
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
