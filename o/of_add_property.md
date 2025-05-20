# Function: <code>of_add_property</code>

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
int of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6ba58)
Location: drivers/of/base.c:1837
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
```
**Symbols:**

```
ffff800010b6ba58-ffff800010b6bb84: of_add_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4ee18)
Location: drivers/of/base.c:1837
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-omap2/timer.c:omap_timer_add_disabled_property
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
**Symbols:**

```
c0c4ee18-c0c4eebc: of_add_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c45980)
Location: drivers/of/base.c:1837
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
  - arch/powerpc/kernel/machine_kexec_64.c:export_htab_values
  - arch/powerpc/kernel/machine_kexec_64.c:export_htab_values
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
**Symbols:**

```
c000000000c45980-c000000000c45ab0: of_add_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_add_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000720ee0)
Location: drivers/of/base.c:1837
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
**Symbols:**

```
ffffffe000720ee0-ffffffe000720f92: of_add_property (STB_GLOBAL)
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
