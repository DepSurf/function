# Function: <code>uniphier_pinctrl_probe</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uniphier_pinctrl_probe(struct platform_device *pdev, const struct uniphier_pinctrl_socdata *socdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c0857b18)
Location: drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:861
Inline: False
Direct callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-ld4.c:uniphier_ld4_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-pro4.c:uniphier_pro4_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-sld8.c:uniphier_sld8_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-pro5.c:uniphier_pro5_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-pxs2.c:uniphier_pxs2_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-ld6b.c:uniphier_ld6b_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-ld11.c:uniphier_ld11_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-ld20.c:uniphier_ld20_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-pxs3.c:uniphier_pxs3_pinctrl_probe
```
**Symbols:**

```
c0857b18-c0857e98: uniphier_pinctrl_probe (STB_GLOBAL)
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
