# Function: <code>soc_device_match</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/sys_soc.h:44
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/sys_soc.h:44
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/sys_soc.h:44
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
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/sys_soc.h:44
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
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/sys_soc.h:44
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
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/sys_soc.h:44
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct soc_device_attribute *soc_device_match(const struct soc_device_attribute *matches);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81b784f0)
Location: drivers/base/soc.c:258
Inline: False
Direct callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
**Symbols:**

```
ffffffff81b784f0-ffffffff81b78574: soc_device_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct soc_device_attribute *soc_device_match(const struct soc_device_attribute *matches);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81bcc2f0)
Location: drivers/base/soc.c:258
Inline: False
Direct callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
**Symbols:**

```
ffffffff81bcc2f0-ffffffff81bcc374: soc_device_match (STB_GLOBAL)
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
const struct soc_device_attribute *soc_device_match(const struct soc_device_attribute *matches);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffff80001091eb18)
Location: drivers/base/soc.c:241
Inline: True
Direct callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_init
  - drivers/clk/renesas/r8a7795-cpg-mssr.c:r8a7795_cpg_mssr_init
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_init
  - drivers/soc/renesas/r8a774c0-sysc.c:r8a774c0_sysc_init
  - drivers/soc/renesas/r8a7795-sysc.c:r8a7795_sysc_init
  - drivers/soc/renesas/r8a77990-sysc.c:r8a77990_sysc_init
```
**Symbols:**

```
ffff80001091eb18-ffff80001091ebe0: soc_device_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct soc_device_attribute *soc_device_match(const struct soc_device_attribute *matches);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0a03e30)
Location: drivers/base/soc.c:241
Inline: True
Direct callers:
  - drivers/clk/renesas/rcar-gen2-cpg.c:rcar_gen2_cpg_init
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_of_xlate
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_of_xlate
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
**Symbols:**

```
c0a03e30-c0a03ef4: soc_device_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct soc_device_attribute *soc_device_match(const struct soc_device_attribute *matches);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0000000009c39e0)
Location: drivers/base/soc.c:241
Inline: True
```
**Symbols:**

```
c0000000009c39e0-c0000000009c3af8: soc_device_match (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
