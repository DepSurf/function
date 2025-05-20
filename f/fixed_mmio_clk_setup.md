# Function: <code>fixed_mmio_clk_setup</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct clk_hw *fixed_mmio_clk_setup(struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-mmio.c (ffff8000107c7e40)
Location: drivers/clk/clk-fixed-mmio.c:18
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_setup
```
**Symbols:**

```
ffff8000107c7e40-ffff8000107c7f68: fixed_mmio_clk_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *fixed_mmio_clk_setup(struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-mmio.c (c08f2dc0)
Location: drivers/clk/clk-fixed-mmio.c:18
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_setup
```
**Symbols:**

```
c08f2dc0-c08f2edc: fixed_mmio_clk_setup (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct clk_hw *fixed_mmio_clk_setup(struct device_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-mmio.c (ffffffe000514b3c)
Location: drivers/clk/clk-fixed-mmio.c:18
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_setup
```
**Symbols:**

```
ffffffe000514b3c-ffffffe000514c22: fixed_mmio_clk_setup (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
