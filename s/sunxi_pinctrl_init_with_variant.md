# Function: <code>sunxi_pinctrl_init_with_variant</code>

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
int sunxi_pinctrl_init_with_variant(struct platform_device *pdev, const struct sunxi_pinctrl_desc *desc, long unsigned int variant);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b6488)
Location: drivers/pinctrl/sunxi/pinctrl-sunxi.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sun4i-a10.c:sun4i_a10_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun5i.c:sun5i_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun6i-a31.c:sun6i_a31_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a23.c:sun8i_a23_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a33.c:sun8i_a33_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun50i-a64.c:a64_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun50i-a64-r.c:sun50i_a64_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a83t.c:sun8i_a83t_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a83t-r.c:sun8i_a83t_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-h3.c:sun8i_h3_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-h3-r.c:sun8i_h3_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-v3s.c:sun8i_v3s_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun50i-h6.c:h6_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun50i-h6-r.c:sun50i_h6_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun9i-a80.c:sun9i_a80_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun9i-a80-r.c:sun9i_a80_r_pinctrl_probe
```
**Symbols:**

```
ffff8000106b6488-ffff8000106b6bec: sunxi_pinctrl_init_with_variant (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
