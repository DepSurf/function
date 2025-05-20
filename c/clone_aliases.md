# Function: <code>clone_aliases</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0d1a)
Location: drivers/iommu/amd_iommu.c:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff816df200-ffffffff816df24a: clone_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798c72)
Location: drivers/iommu/amd/iommu.c:225
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
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
In drivers/iommu/amd/iommu.c (ffffffff817a74f2)
Location: drivers/iommu/amd/iommu.c:234
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
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
In drivers/iommu/amd/iommu.c (ffffffff81788e75)
Location: drivers/iommu/amd/iommu.c:190
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
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
In drivers/iommu/amd/iommu.c (ffffffff8180fa65)
Location: drivers/iommu/amd/iommu.c:190
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
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
In drivers/iommu/amd/iommu.c (ffffffff8194ebd5)
Location: drivers/iommu/amd/iommu.c:191
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
  - drivers/iommu/amd/iommu.c:setup_aliases
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab3efb)
Location: drivers/iommu/amd/iommu.c:242
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff81ab3d40-ffffffff81ab3da1: clone_aliases.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b009eb)
Location: drivers/iommu/amd/iommu.c:242
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff81b00830-ffffffff81b00891: clone_aliases.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b56d71)
Location: drivers/iommu/amd/iommu.c:245
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff81b54260-ffffffff81b542c1: clone_aliases.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a676a)
Location: drivers/iommu/amd_iommu.c:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff816a4c50-ffffffff816a4c9a: clone_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168415a)
Location: drivers/iommu/amd_iommu.c:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff81682640-ffffffff8168268a: clone_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d49da)
Location: drivers/iommu/amd_iommu.c:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff816d2ec0-ffffffff816d2f0a: clone_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ef0da)
Location: drivers/iommu/amd_iommu.c:245
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
Direct callers:
  - drivers/iommu/amd_iommu.c:update_domain
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff816ed560-ffffffff816ed5aa: clone_aliases.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
