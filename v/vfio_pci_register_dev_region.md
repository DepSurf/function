# Function: <code>vfio_pci_register_dev_region</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d8170)
Location: drivers/vfio/pci/vfio_pci.c:665
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff817d8170-ffffffff817d8283: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a5a60)
Location: drivers/vfio/pci/vfio_pci.c:728
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
```
**Symbols:**

```
ffffffff818a5a60-ffffffff818a5b73: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b4b90)
Location: drivers/vfio/pci/vfio_pci.c:768
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
```
**Symbols:**

```
ffffffff818b4b90-ffffffff818b4ca3: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81898020)
Location: drivers/vfio/pci/vfio_pci.c:750
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
```
**Symbols:**

```
ffffffff81898020-ffffffff81898133: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_core_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928800)
Location: drivers/vfio/pci/vfio_pci_core.c:610
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
```
**Symbols:**

```
ffffffff81928800-ffffffff81928913: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_core_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7e720)
Location: drivers/vfio/pci/vfio_pci_core.c:647
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init
```
**Symbols:**

```
ffffffff81a7e720-ffffffff81a7e7db: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab7bc0)
Location: drivers/vfio/pci/vfio_pci.c:665
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init
```
**Symbols:**

```
c000000000ab7bc0-c000000000ab7cf4: vfio_pci_register_dev_region (STB_GLOBAL)
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81782220)
Location: drivers/vfio/pci/vfio_pci.c:665
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff81782220-ffffffff81782333: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817ccff0)
Location: drivers/vfio/pci/vfio_pci.c:665
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff817ccff0-ffffffff817cd103: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pci_register_dev_region(struct vfio_pci_device *vdev, unsigned int type, unsigned int subtype, const struct vfio_pci_regops *ops, size_t size, u32 flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e7290)
Location: drivers/vfio/pci/vfio_pci.c:665
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff817e7290-ffffffff817e73a3: vfio_pci_register_dev_region (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device *vdev</code> ➡️ <code>struct vfio_pci_core_device *vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
