# Function: <code>iommu_unregister_device_fault_handler</code>

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
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b64a0)
Location: drivers/iommu/iommu.c:942
Inline: False
```
**Symbols:**

```
ffffffff816b64a0-ffffffff816b651e: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d91a0)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
ffffffff816d91a0-ffffffff816d921e: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d6e0)
Location: drivers/iommu/iommu.c:1101
Inline: False
```
**Symbols:**

```
ffffffff8178d6e0-ffffffff8178d75e: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b8c50)
Location: drivers/iommu/iommu.c:1122
Inline: False
```
**Symbols:**

```
ffffffff817b8c50-ffffffff817b8cce: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179be60)
Location: drivers/iommu/iommu.c:1151
Inline: False
```
**Symbols:**

```
ffffffff8179be60-ffffffff8179bede: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81824b50)
Location: drivers/iommu/iommu.c:1166
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
```
**Symbols:**

```
ffffffff81824b50-ffffffff81824bce: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81964ae0)
Location: drivers/iommu/iommu.c:1140
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
```
**Symbols:**

```
ffffffff81964ae0-ffffffff81964b5d: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acdbd0)
Location: drivers/iommu/iommu.c:1261
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
```
**Symbols:**

```
ffffffff81acdbd0-ffffffff81acdc4d: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1ce60)
Location: drivers/iommu/iommu.c:1252
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81b1ce60-ffffffff81b1cedd: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b733e0)
Location: drivers/iommu/iommu.c:1396
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff81b733e0-ffffffff81b7345d: iommu_unregister_device_fault_handler (STB_GLOBAL)
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
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c49c0)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
ffff8000108c49c0-ffff8000108c4a4c: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bbdd4)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
c09bbdd4-c09bbe54: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096a7c0)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
c00000000096a7c0-c00000000096a890: iommu_unregister_device_fault_handler (STB_GLOBAL)
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
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169ebf0)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
ffffffff8169ebf0-ffffffff8169ec6e: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c5e0)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
ffffffff8167c5e0-ffffffff8167c65e: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cce60)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
ffffffff816cce60-ffffffff816ccede: iommu_unregister_device_fault_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_unregister_device_fault_handler(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7340)
Location: drivers/iommu/iommu.c:998
Inline: False
```
**Symbols:**

```
ffffffff816e7340-ffffffff816e73be: iommu_unregister_device_fault_handler (STB_GLOBAL)
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
