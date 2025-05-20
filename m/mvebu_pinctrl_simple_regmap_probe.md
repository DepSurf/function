# Function: <code>mvebu_pinctrl_simple_regmap_probe</code>

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
int mvebu_pinctrl_simple_regmap_probe(struct platform_device *pdev, struct device *syscon_dev, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106ab418)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:811
Inline: False
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-ap806.c:armada_ap806_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-cp110.c:armada_cp110_pinctrl_probe
```
**Symbols:**

```
ffff8000106ab418-ffff8000106ab4cc: mvebu_pinctrl_simple_regmap_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mvebu_pinctrl_simple_regmap_probe(struct platform_device *pdev, struct device *syscon_dev, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084b284)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:811
Inline: False
```
**Symbols:**

```
c084b284-c084b320: mvebu_pinctrl_simple_regmap_probe (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
