# Function: <code>device_match_fwnode</code>

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
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9d90)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
ffffffff816f9d90-ffffffff816f9dae: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2d70)
Location: drivers/base/core.c:4062
Inline: False
```
**Symbols:**

```
ffffffff817b2d70-ffffffff817b2d91: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c77d0)
Location: drivers/base/core.c:4518
Inline: False
```
**Symbols:**

```
ffffffff817c77d0-ffffffff817c77f1: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aac40)
Location: drivers/base/core.c:4745
Inline: False
```
**Symbols:**

```
ffffffff817aac40-ffffffff817aac61: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833e00)
Location: drivers/base/core.c:4817
Inline: False
```
**Symbols:**

```
ffffffff81833e00-ffffffff81833e21: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975620)
Location: drivers/base/core.c:4856
Inline: False
```
**Symbols:**

```
ffffffff81975620-ffffffff81975649: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae10e0)
Location: drivers/base/core.c:5075
Inline: False
Direct callers:
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/viot.c:viot_dev_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_match_node
```
**Symbols:**

```
ffffffff81ae10e0-ffffffff81ae1109: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2f330)
Location: drivers/base/core.c:5084
Inline: False
Direct callers:
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/viot.c:viot_dev_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_match_node
```
**Symbols:**

```
ffffffff81b2f330-ffffffff81b2f359: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b86b30)
Location: drivers/base/core.c:5098
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_device_find_by_fwnode
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/viot.c:viot_dev_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_match_node
```
**Symbols:**

```
ffffffff81b86b30-ffffffff81b86b59: device_match_fwnode (STB_GLOBAL)
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
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4298)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
ffff8000108e4298-ffff8000108e42d0: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d2d9c)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
c09d2d9c-c09d2dc8: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000979770)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
c000000000979770-c0000000009797bc: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579288)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
ffffffe000579288-ffffffe0005792be: device_match_fwnode (STB_GLOBAL)
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
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf580)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
ffffffff816bf580-ffffffff816bf59e: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a830)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
ffffffff8169a830-ffffffff8169a84e: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816eda50)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
ffffffff816eda50-ffffffff816eda6e: device_match_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_match_fwnode(struct device *dev, const void *fwnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708290)
Location: drivers/base/core.c:3589
Inline: False
```
**Symbols:**

```
ffffffff81708290-ffffffff817082ae: device_match_fwnode (STB_GLOBAL)
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
