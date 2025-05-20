# Function: <code>omap_i2c_reset</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-omap.c (ffff800010abc4cc)
Location: drivers/i2c/busses/i2c-omap.c:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
Direct callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
```
**Symbols:**

```
ffff800010abb4b8-ffff800010abb5b0: omap_i2c_reset.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int omap_i2c_reset(struct omap_hwmod *oh);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/mach-omap2/i2c.c (c03368e0)
Location: arch/arm/mach-omap2/i2c.c:36
Inline: False
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9daf4)
Location: drivers/i2c/busses/i2c-omap.c:309
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
Direct callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
```
**Symbols:**

```
c0b9d054-c0b9d148: omap_i2c_reset.part.0 (STB_LOCAL)
c03368e0-c0336a24: omap_i2c_reset (STB_GLOBAL)
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
