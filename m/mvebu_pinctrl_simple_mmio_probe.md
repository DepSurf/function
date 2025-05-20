# Function: <code>mvebu_pinctrl_simple_mmio_probe</code>

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
int mvebu_pinctrl_simple_mmio_probe(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106ab260)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:758
Inline: False
```
**Symbols:**

```
ffff8000106ab260-ffff8000106ab31c: mvebu_pinctrl_simple_mmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mvebu_pinctrl_simple_mmio_probe(struct platform_device *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084b0f8)
Location: drivers/pinctrl/mvebu/pinctrl-mvebu.c:758
Inline: False
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-370.c:armada_370_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-375.c:armada_375_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-38x.c:armada_38x_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-39x.c:armada_39x_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-xp.c:armada_xp_pinctrl_probe
```
**Symbols:**

```
c084b0f8-c084b19c: mvebu_pinctrl_simple_mmio_probe (STB_GLOBAL)
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
