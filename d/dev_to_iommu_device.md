# Function: <code>dev_to_iommu_device</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/iommu.h:268
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/iommu.h:268
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/iommu.h:277
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff81635312)
Location: include/linux/iommu.h:277
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bc55)
Location: include/linux/iommu.h:277
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff816708e5)
Location: include/linux/iommu.h:277
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a3a5)
Location: include/linux/iommu.h:268
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168ec85)
Location: include/linux/iommu.h:268
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1d55)
Location: include/linux/iommu.h:376
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c61b5)
Location: include/linux/iommu.h:376
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4c75)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e91e5)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179ad25)
Location: include/linux/iommu.h:403
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_features
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a01f5)
Location: include/linux/iommu.h:403
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel/iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel/iommu.c:intel_iommu_show_address
  - drivers/iommu/intel/iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9048)
Location: include/linux/iommu.h:399
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_features
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff817adcf5)
Location: include/linux/iommu.h:399
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel/iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel/iommu.c:intel_iommu_show_address
  - drivers/iommu/intel/iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178ad38)
Location: include/linux/iommu.h:366
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_features
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff81790705)
Location: include/linux/iommu.h:366
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel/iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel/iommu.c:intel_iommu_show_address
  - drivers/iommu/intel/iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81811dd8)
Location: include/linux/iommu.h:393
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_features
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff81818005)
Location: include/linux/iommu.h:393
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:domains_supported_show
  - drivers/iommu/intel/iommu.c:ecap_show
  - drivers/iommu/intel/iommu.c:cap_show
  - drivers/iommu/intel/iommu.c:address_show
  - drivers/iommu/intel/iommu.c:version_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81952c38)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_features
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff81959125)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:domains_supported_show
  - drivers/iommu/intel/iommu.c:ecap_show
  - drivers/iommu/intel/iommu.c:cap_show
  - drivers/iommu/intel/iommu.c:address_show
  - drivers/iommu/intel/iommu.c:version_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab8168)
Location: include/linux/iommu.h:433
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_features
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0255)
Location: include/linux/iommu.h:433
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:domains_supported_show
  - drivers/iommu/intel/iommu.c:ecap_show
  - drivers/iommu/intel/iommu.c:cap_show
  - drivers/iommu/intel/iommu.c:address_show
  - drivers/iommu/intel/iommu.c:version_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b04818)
Location: include/linux/iommu.h:440
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_features
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0cb05)
Location: include/linux/iommu.h:440
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:domains_supported_show
  - drivers/iommu/intel/iommu.c:ecap_show
  - drivers/iommu/intel/iommu.c:cap_show
  - drivers/iommu/intel/iommu.c:address_show
  - drivers/iommu/intel/iommu.c:version_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58448)
Location: include/linux/iommu.h:652
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b612b5)
Location: include/linux/iommu.h:652
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:domains_supported_show
  - drivers/iommu/intel/iommu.c:ecap_show
  - drivers/iommu/intel/iommu.c:cap_show
  - drivers/iommu/intel/iommu.c:address_show
  - drivers/iommu/intel/iommu.c:version_show
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa755)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff816aecc5)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81687f45)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168c625)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8935)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dcea5)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2ee5)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_features
  - drivers/iommu/amd_iommu_init.c:amd_iommu_show_cap
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f74e5)
Location: include/linux/iommu.h:391
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ecap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_cap
  - drivers/iommu/intel-iommu.c:intel_iommu_show_address
  - drivers/iommu/intel-iommu.c:intel_iommu_show_version
```
</details>
</li>
</ul>

## Differences
