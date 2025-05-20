# Function: <code>get_dev_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:184
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:351
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:352
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:383
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c0fc)
Location: drivers/iommu/amd_iommu.c:321
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff8162a6c0-ffffffff8162a6d2: get_dev_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8166760f)
Location: drivers/iommu/amd_iommu.c:317
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81665370-ffffffff81665382: get_dev_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685cbf)
Location: drivers/iommu/amd_iommu.c:327
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81683970-ffffffff81683982: get_dev_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bd41f)
Location: drivers/iommu/amd_iommu.c:315
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff816bb140-ffffffff816bb152: get_dev_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e03ff)
Location: drivers/iommu/amd_iommu.c:302
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff816ddf40-ffffffff816ddf52: get_dev_data (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a5e4f)
Location: drivers/iommu/amd_iommu.c:302
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff816a3990-ffffffff816a39a2: get_dev_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168383f)
Location: drivers/iommu/amd_iommu.c:302
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81681380-ffffffff81681392: get_dev_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d40bf)
Location: drivers/iommu/amd_iommu.c:302
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff816d1c00-ffffffff816d1c12: get_dev_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct iommu_dev_data *get_dev_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ee7bf)
Location: drivers/iommu/amd_iommu.c:302
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff816ec1c0-ffffffff816ec1d2: get_dev_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
