# Function: <code>intel_svm_device_to_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153b4c0)
Location: drivers/iommu/intel-iommu.c:5073
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8153b4c0-ffffffff8153b557: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158ffd0)
Location: drivers/iommu/intel-iommu.c:5211
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8158ffd0-ffffffff8159006d: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bd860)
Location: drivers/iommu/intel-iommu.c:5364
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff815bd860-ffffffff815bd8fd: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d3460)
Location: drivers/iommu/intel-iommu.c:5398
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff815d3460-ffffffff815d34fd: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8163a160)
Location: drivers/iommu/intel-iommu.c:5313
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8163a160-ffffffff8163a1fd: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816752e0)
Location: drivers/iommu/intel-iommu.c:5351
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816752e0-ffffffff8167537d: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81693780)
Location: drivers/iommu/intel-iommu.c:5361
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81693780-ffffffff81693800: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5513
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816cc6a9-ffffffff816cc6d8: intel_svm_device_to_iommu.cold (STB_LOCAL)
ffffffff816cbc10-ffffffff816cbc71: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5814
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816efeff-ffffffff816eff2e: intel_svm_device_to_iommu.cold (STB_LOCAL)
ffffffff816ef4f0-ffffffff816ef551: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5834
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff817a742b-ffffffff817a745a: intel_svm_device_to_iommu.cold (STB_LOCAL)
ffffffff817a6970-ffffffff817a69cf: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5814
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816b56e5-ffffffff816b5714: intel_svm_device_to_iommu.cold (STB_LOCAL)
ffffffff816b4ce0-ffffffff816b4d41: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5814
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8169332f-ffffffff8169335e: intel_svm_device_to_iommu.cold (STB_LOCAL)
ffffffff81692920-ffffffff81692981: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5814
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816e3bbf-ffffffff816e3bee: intel_svm_device_to_iommu.cold (STB_LOCAL)
ffffffff816e31b0-ffffffff816e3211: intel_svm_device_to_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct intel_iommu *intel_svm_device_to_iommu(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:5814
Inline: False
Direct callers:
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff816fe26b-ffffffff816fe29a: intel_svm_device_to_iommu.cold (STB_LOCAL)
ffffffff816fd840-ffffffff816fd8a1: intel_svm_device_to_iommu (STB_GLOBAL)
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
