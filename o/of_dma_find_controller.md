# Function: <code>of_dma_find_controller</code>

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
In drivers/dma/of-dma.c (ffff8000107ff658)
Location: drivers/dma/of-dma.c:30
Inline: True
Direct callers:
  - drivers/dma/of-dma.c:of_dma_router_xlate
```
**Symbols:**

```
ffff8000107ff658-ffff8000107ff6f8: of_dma_find_controller.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct of_dma *of_dma_find_controller(struct of_phandle_args *dma_spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/of-dma.c (c091feb0)
Location: drivers/dma/of-dma.c:30
Inline: True
Direct callers:
  - drivers/dma/of-dma.c:of_dma_router_xlate
```
**Symbols:**

```
c091feb0-c091ff3c: of_dma_find_controller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/of-dma.c (c0000000008c96a0)
Location: drivers/dma/of-dma.c:30
Inline: True
Direct callers:
  - drivers/dma/of-dma.c:of_dma_router_xlate
```
**Symbols:**

```
c0000000008c96a0-c0000000008c9748: of_dma_find_controller.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/of-dma.c (ffffffe0005178ce)
Location: drivers/dma/of-dma.c:30
Inline: True
Direct callers:
  - drivers/dma/of-dma.c:of_dma_router_xlate
```
**Symbols:**

```
ffffffe0005178ce-ffffffe00051794c: of_dma_find_controller.isra.0 (STB_LOCAL)
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
