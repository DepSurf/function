# Function: <code>driver_find_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8154c750)
Location: drivers/base/driver.c:77
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_pdevname
```
**Symbols:**

```
ffffffff8154c750-ffffffff8154c811: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8159e540)
Location: drivers/base/driver.c:77
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_pdevname
```
**Symbols:**

```
ffffffff8159e540-ffffffff8159e601: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815ccaf0)
Location: drivers/base/driver.c:77
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_pdevname
```
**Symbols:**

```
ffffffff815ccaf0-ffffffff815ccbb1: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff815e1650)
Location: drivers/base/driver.c:77
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_pdevname
```
**Symbols:**

```
ffffffff815e1650-ffffffff815e170b: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816487a0)
Location: drivers/base/driver.c:77
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_pdevname
```
**Symbols:**

```
ffffffff816487a0-ffffffff81648861: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81683d60)
Location: drivers/base/driver.c:75
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_pdevname
```
**Symbols:**

```
ffffffff81683d60-ffffffff81683e1b: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816a3a30)
Location: drivers/base/driver.c:75
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_pdevname
```
**Symbols:**

```
ffffffff816a3a30-ffffffff816a3aeb: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816dc920)
Location: drivers/base/driver.c:75
Inline: False
```
**Symbols:**

```
ffffffff816dc920-ffffffff816dc9dd: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817009c0)
Location: drivers/base/driver.c:75
Inline: False
```
**Symbols:**

```
ffffffff817009c0-ffffffff81700a80: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817ba910)
Location: drivers/base/driver.c:76
Inline: False
```
**Symbols:**

```
ffffffff817ba910-ffffffff817ba9d0: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817cf550)
Location: drivers/base/driver.c:76
Inline: False
```
**Symbols:**

```
ffffffff817cf550-ffffffff817cf613: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff817b2f60)
Location: drivers/base/driver.c:76
Inline: False
```
**Symbols:**

```
ffffffff817b2f60-ffffffff817b3023: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8183c450)
Location: drivers/base/driver.c:76
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff8183c450-ffffffff8183c513: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8197ee50)
Location: drivers/base/driver.c:145
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff8197ee50-ffffffff8197ef2e: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81aec540)
Location: drivers/base/driver.c:151
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81aec540-ffffffff81aec61e: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b3a730)
Location: drivers/base/driver.c:151
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81b3a730-ffffffff81b3a80e: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b921f0)
Location: drivers/base/driver.c:151
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
**Symbols:**

```
ffffffff81b921f0-ffffffff81b922ce: driver_find_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffff8000108ebdd0)
Location: drivers/base/driver.c:75
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_add_device
  - drivers/iommu/virtio-iommu.c:viommu_add_device
  - drivers/mfd/altera-sysmgr.c:altr_sysmgr_regmap_lookup_by_phandle
```
**Symbols:**

```
ffff8000108ebdd0-ffff8000108ebeb0: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c09d9e30)
Location: drivers/base/driver.c:75
Inline: False
Direct callers:
  - drivers/amba/tegra-ahb.c:tegra_ahb_enable_smmu
```
**Symbols:**

```
c09d9e30-c09d9f0c: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (c0000000009836a0)
Location: drivers/base/driver.c:75
Inline: False
```
**Symbols:**

```
c0000000009836a0-c0000000009837e0: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffe00057f474)
Location: drivers/base/driver.c:75
Inline: False
```
**Symbols:**

```
ffffffe00057f474-ffffffe00057f504: driver_find_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816c61b0)
Location: drivers/base/driver.c:75
Inline: False
```
**Symbols:**

```
ffffffff816c61b0-ffffffff816c6270: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816a1410)
Location: drivers/base/driver.c:75
Inline: False
```
**Symbols:**

```
ffffffff816a1410-ffffffff816a14d0: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff816f4680)
Location: drivers/base/driver.c:75
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_find_device
```
**Symbols:**

```
ffffffff816f4680-ffffffff816f4740: driver_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *driver_find_device(struct device_driver *drv, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8170ef10)
Location: drivers/base/driver.c:75
Inline: False
```
**Symbols:**

```
ffffffff8170ef10-ffffffff8170efd0: driver_find_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*match)(struct device *, void *)</code> ➡️ <code>int (*match)(struct device *, const void *)</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
