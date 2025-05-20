# Function: <code>iommu_domain_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81529ec0)
Location: drivers/iommu/iommu.c:1085
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff81529ec0-ffffffff81529ed2: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157efc6)
Location: drivers/iommu/iommu.c:1075
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff8157d310-ffffffff8157d322: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aba56)
Location: drivers/iommu/iommu.c:1226
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff815a97d0-ffffffff815a97e2: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c1725)
Location: drivers/iommu/iommu.c:1276
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff815bf370-ffffffff815bf382: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627eeb)
Location: drivers/iommu/iommu.c:1277
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff81625970-ffffffff81625988: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81662aa6)
Location: drivers/iommu/iommu.c:1278
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff81660810-ffffffff81660828: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81681086)
Location: drivers/iommu/iommu.c:1345
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff8167ecc0-ffffffff8167ecd8: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b7a20)
Location: drivers/iommu/iommu.c:1562
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff816b5a80-ffffffff816b5a98: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816da750)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff816d8760-ffffffff816d8778: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d23e)
Location: drivers/iommu/iommu.c:1905
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff8178ced0-ffffffff8178cee8: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bbdb6)
Location: drivers/iommu/iommu.c:1935
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_enable_iommu
```
**Symbols:**

```
ffffffff817b88f0-ffffffff817b8908: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179ef20)
Location: drivers/iommu/iommu.c:1956
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_enable_iommu
```
**Symbols:**

```
ffffffff8179bb50-ffffffff8179bb68: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81827ed6)
Location: drivers/iommu/iommu.c:1976
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_enable_iommu
```
**Symbols:**

```
ffffffff81825250-ffffffff8182527a: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81967e67)
Location: drivers/iommu/iommu.c:1936
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_enable_iommu
```
**Symbols:**

```
ffffffff81965460-ffffffff81965490: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ace9f0)
Location: drivers/iommu/iommu.c:1961
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu-sva.c:iommu_sva_unbind_device
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_enable_iommu
```
**Symbols:**

```
ffffffff81ace9f0-ffffffff81acea39: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1d400)
Location: drivers/iommu/iommu.c:1948
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu-sva.c:iommu_sva_unbind_device
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_enable_iommu
```
**Symbols:**

```
ffffffff81b1d400-ffffffff81b1d448: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b73980)
Location: drivers/iommu/iommu.c:2214
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc_user
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:iommu_setup_default_domain
  - drivers/iommu/iommu.c:__iommu_domain_alloc
  - drivers/iommu/iommu.c:iommu_deinit_device
  - drivers/iommu/iommu.c:iommu_deinit_device
  - drivers/iommu/iommu-sva.c:iommu_sva_unbind_device
  - drivers/iommu/iommu-sva.c:iommu_sva_bind_device
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_enable_iommu
```
**Symbols:**

```
ffffffff81b73980-ffffffff81b739cd: iommu_domain_free (STB_GLOBAL)
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
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c6808)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffff8000108c3d50-ffff8000108c3d84: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd574)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - arch/arm/mm/dma-mapping.c:release_iommu_mapping
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
c09bb2e8-c09bb30c: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096c398)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
c0000000009697e0-c000000000969824: iommu_domain_free (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a01a0)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff8169e1b0-ffffffff8169e1c8: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167db90)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8167bba0-ffffffff8167bbb8: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce410)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff816cc420-ffffffff816cc438: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_domain_free(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8960)
Location: drivers/iommu/iommu.c:1618
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_release
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff816e68f0-ffffffff816e6908: iommu_domain_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
