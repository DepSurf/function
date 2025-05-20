# Function: <code>meson_gx_pwrc_vpu_setup_clk</code>

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
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (ffff800010819f90)
Location: drivers/soc/amlogic/meson-gx-pwrc-vpu.c:128
Inline: True
Direct callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
**Symbols:**

```
ffff800010819f90-ffff80001081a05c: meson_gx_pwrc_vpu_setup_clk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int meson_gx_pwrc_vpu_setup_clk(struct meson_gx_pwrc_vpu *pd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (c0936cac)
Location: drivers/soc/amlogic/meson-gx-pwrc-vpu.c:128
Inline: True
Direct callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
**Symbols:**

```
c0936cac-c0936d4c: meson_gx_pwrc_vpu_setup_clk (STB_LOCAL)
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
