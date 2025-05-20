# Function: <code>mtk_smi_clk_enable</code>

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
In drivers/memory/mtk-smi.c (ffff800010b8c234)
Location: drivers/memory/mtk-smi.c:89
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
Direct callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
```
**Symbols:**

```
ffff800010b8c040-ffff800010b8c128: mtk_smi_clk_enable.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/memory/mtk-smi.c (c0c731e4)
Location: drivers/memory/mtk-smi.c:89
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
Direct callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
```
**Symbols:**

```
c0c73014-c0c730ec: mtk_smi_clk_enable.part.0 (STB_LOCAL)
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
