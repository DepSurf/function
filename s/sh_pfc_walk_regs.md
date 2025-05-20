# Function: <code>sh_pfc_walk_regs</code>

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
unsigned int sh_pfc_walk_regs(struct sh_pfc *pfc, void (*do_reg)(struct sh_pfc *, u32, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106af4c0)
Location: drivers/pinctrl/sh-pfc/core.c:639
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_resume_noirq
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_suspend_noirq
```
**Symbols:**

```
ffff8000106af4c0-ffff8000106af634: sh_pfc_walk_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int sh_pfc_walk_regs(struct sh_pfc *pfc, void (*do_reg)(struct sh_pfc *, u32, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (c0852e54)
Location: drivers/pinctrl/sh-pfc/core.c:639
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_resume_noirq
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_suspend_noirq
```
**Symbols:**

```
c0852e54-c0852fbc: sh_pfc_walk_regs (STB_LOCAL)
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
