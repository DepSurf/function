# Function: <code>sunxi_usb_clk_setup</code>

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
void sunxi_usb_clk_setup(struct device_node *node, const struct usb_clk_data *data, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/sunxi/clk-usb.c (ffff80001148e048)
Location: drivers/clk/sunxi/clk-usb.c:88
Inline: False
Direct callers:
  - drivers/clk/sunxi/clk-usb.c:sun9i_a80_usb_phy_setup
  - drivers/clk/sunxi/clk-usb.c:sun9i_a80_usb_mod_setup
  - drivers/clk/sunxi/clk-usb.c:sun8i_h3_usb_setup
  - drivers/clk/sunxi/clk-usb.c:sun8i_a23_usb_setup
  - drivers/clk/sunxi/clk-usb.c:sun6i_a31_usb_setup
  - drivers/clk/sunxi/clk-usb.c:sun5i_a13_usb_setup
  - drivers/clk/sunxi/clk-usb.c:sun4i_a10_usb_setup
```
**Symbols:**

```
ffff80001148e048-ffff80001148e2bc: sunxi_usb_clk_setup (STB_LOCAL)
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
