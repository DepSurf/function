# Function: <code>sunxi_r_ccu_init</code>

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
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void sunxi_r_ccu_init(struct device_node *node, const struct sunxi_ccu_desc *desc);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c (ffff80001148e6a0)
Location: drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c:188
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun50i-h6-r.c:sun50i_h6_r_ccu_setup
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-r.c (ffff80001148e86c)
Location: drivers/clk/sunxi-ng/ccu-sun8i-r.c:257
Inline: False
Direct callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-r.c:sun50i_a64_r_ccu_setup
  - drivers/clk/sunxi-ng/ccu-sun8i-r.c:sun8i_h3_r_ccu_setup
  - drivers/clk/sunxi-ng/ccu-sun8i-r.c:sun8i_a83t_r_ccu_setup
```
**Symbols:**

```
ffff80001148e86c-ffff80001148e8e0: sunxi_r_ccu_init (STB_LOCAL)
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
