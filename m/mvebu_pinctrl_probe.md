# Function: <code>mvebu_pinctrl_probe</code>

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
int mvebu_pinctrl_probe(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aaa60)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:568
Inline: False
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
```
**Symbols:**

```
ffff8000106aaa60-ffff8000106ab25c: mvebu_pinctrl_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mvebu_pinctrl_probe(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a878)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:568
Inline: False
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
```
**Symbols:**

```
c084a878-c084b0f8: mvebu_pinctrl_probe (STB_GLOBAL)
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
