# Function: <code>__imx_clk_scu</code>

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
struct clk_hw *__imx_clk_scu(const char *name, const const char * *parents, int num_parents, u32 rsrc_id, u8 clk_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-scu.c (ffff8000107d74c0)
Location: drivers/clk/imx/clk-scu.c:347
Inline: False
Direct callers:
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
```
**Symbols:**

```
ffff8000107d74c0-ffff8000107d75bc: __imx_clk_scu (STB_GLOBAL)
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
