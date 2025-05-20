# Function: <code>iommu_register_device_fault_handler</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b63c0)
Location: drivers/iommu/iommu.c:897
Inline: False
```
**Symbols:**

```
ffffffff816b63c0-ffffffff816b6498: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d90c0)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
ffffffff816d90c0-ffffffff816d9198: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178e030)
Location: drivers/iommu/iommu.c:1056
Inline: False
```
**Symbols:**

```
ffffffff8178e030-ffffffff8178e10b: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9da0)
Location: drivers/iommu/iommu.c:1077
Inline: False
```
**Symbols:**

```
ffffffff817b9da0-ffffffff817b9e7b: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179d010)
Location: drivers/iommu/iommu.c:1106
Inline: False
```
**Symbols:**

```
ffffffff8179d010-ffffffff8179d0eb: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81825ce0)
Location: drivers/iommu/iommu.c:1121
Inline: False
```
**Symbols:**

```
ffffffff81825ce0-ffffffff81825dbb: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965990)
Location: drivers/iommu/iommu.c:1095
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81965990-ffffffff81965a73: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acee90)
Location: drivers/iommu/iommu.c:1216
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81acee90-ffffffff81acef73: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1da00)
Location: drivers/iommu/iommu.c:1207
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81b1da00-ffffffff81b1dae3: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b746f0)
Location: drivers/iommu/iommu.c:1351
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81b746f0-ffffffff81b74802: iommu_register_device_fault_handler (STB_GLOBAL)
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
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c48d8)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
ffff8000108c48d8-ffff8000108c49bc: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bbd00)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
c09bbd00-c09bbdd4: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096d1d0)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
c00000000096d1d0-c00000000096d30c: iommu_register_device_fault_handler (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169eb10)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
ffffffff8169eb10-ffffffff8169ebe8: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c500)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
ffffffff8167c500-ffffffff8167c5d8: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ccd80)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
ffffffff816ccd80-ffffffff816cce58: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_register_device_fault_handler(struct device *dev, iommu_dev_fault_handler_t handler, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7260)
Location: drivers/iommu/iommu.c:953
Inline: False
```
**Symbols:**

```
ffffffff816e7260-ffffffff816e7338: iommu_register_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
