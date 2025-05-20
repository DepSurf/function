# Function: <code>sh_pfc_phys_to_virt</code>

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
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afaa8)
Location: drivers/pinctrl/sh-pfc/core.c:87
Inline: True
Direct callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_read
```
**Symbols:**

```
ffff8000106afaa8-ffff8000106afb30: sh_pfc_phys_to_virt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *sh_pfc_phys_to_virt(struct sh_pfc *pfc, u32 reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (c08534a8)
Location: drivers/pinctrl/sh-pfc/core.c:87
Inline: True
Direct callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
```
**Symbols:**

```
c08534a8-c0853510: sh_pfc_phys_to_virt (STB_LOCAL)
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
