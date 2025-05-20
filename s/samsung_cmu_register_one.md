# Function: <code>samsung_cmu_register_one</code>

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
struct samsung_clk_provider *samsung_cmu_register_one(struct device_node *np, const struct samsung_cmu_info *cmu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/samsung/clk.c (c1584948)
Location: drivers/clk/samsung/clk.c:346
Inline: False
Direct callers:
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_top_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_peri_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_mif_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_mfc_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_kfc_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_isp_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_gscl_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_g3d_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_g2d_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_fsys_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_egl_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_disp_init
  - drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_aud_init
  - drivers/clk/samsung/clk-exynos5410.c:exynos5410_clk_init
```
**Symbols:**

```
c1584948-c1584a7c: samsung_cmu_register_one (STB_GLOBAL)
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
