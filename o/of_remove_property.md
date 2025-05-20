# Function: <code>of_remove_property</code>

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
int of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6bc10)
Location: drivers/of/base.c:1886
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
**Symbols:**

```
ffff800010b6bc10-ffff800010b6bd90: of_remove_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4ef34)
Location: drivers/of/base.c:1886
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
**Symbols:**

```
c0c4ef34-c0c4f018: of_remove_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c45b30)
Location: drivers/of/base.c:1886
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
  - arch/powerpc/kernel/machine_kexec.c:kexec_setup
  - arch/powerpc/kernel/machine_kexec_64.c:export_htab_values
  - arch/powerpc/kernel/machine_kexec_64.c:export_htab_values
  - arch/powerpc/kernel/ima_kexec.c:ima_free_kexec_buffer
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/iommu.c:remove_ddw
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
**Symbols:**

```
c000000000c45b30-c000000000c45c7c: of_remove_property (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_remove_property(struct device_node *np, struct property *prop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000720ff4)
Location: drivers/of/base.c:1886
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
**Symbols:**

```
ffffffe000720ff4-ffffffe0007210cc: of_remove_property (STB_GLOBAL)
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
