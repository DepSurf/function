# Function: <code>of_dma_controller_register</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/of_dma.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/of_dma.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/of_dma.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/of_dma.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/of_dma.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (0)
Location: include/linux/of_dma.h:55
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int of_dma_controller_register(struct device_node *np, struct dma_chan * (*of_dma_xlate)(struct of_phandle_args *, struct of_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/of-dma.c (ffff8000107ff4b8)
Location: drivers/dma/of-dma.c:101
Inline: True
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
**Symbols:**

```
ffff8000107ff4b8-ffff8000107ff57c: of_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int of_dma_controller_register(struct device_node *np, struct dma_chan * (*of_dma_xlate)(struct of_phandle_args *, struct of_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/of-dma.c (c091fd18)
Location: drivers/dma/of-dma.c:101
Inline: True
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
**Symbols:**

```
c091fd18-c091fdd8: of_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int of_dma_controller_register(struct device_node *np, struct dma_chan * (*of_dma_xlate)(struct of_phandle_args *, struct of_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/of-dma.c (c0000000008c9e60)
Location: drivers/dma/of-dma.c:101
Inline: True
```
**Symbols:**

```
c0000000008c9e60-c0000000008c9f6c: of_dma_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int of_dma_controller_register(struct device_node *np, struct dma_chan * (*of_dma_xlate)(struct of_phandle_args *, struct of_dma *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/of-dma.c (ffffffe00051774c)
Location: drivers/dma/of-dma.c:101
Inline: True
```
**Symbols:**

```
ffffffe00051774c-ffffffe000517806: of_dma_controller_register (STB_GLOBAL)
```
</details>
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
