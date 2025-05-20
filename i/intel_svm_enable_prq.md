# Function: <code>intel_svm_enable_prq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8153c590)
Location: drivers/iommu/intel-svm.c:91
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8153c590-ffffffff8153c6f4: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81591110)
Location: drivers/iommu/intel-svm.c:91
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81591110-ffffffff81591274: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815be9e0)
Location: drivers/iommu/intel-svm.c:97
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815be9e0-ffffffff815beb3e: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff815d4600)
Location: drivers/iommu/intel-svm.c:98
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815d4600-ffffffff815d475e: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8163b390)
Location: drivers/iommu/intel-svm.c:99
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8163b390-ffffffff8163b4f5: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:111
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81676b27-ffffffff81676b97: intel_svm_enable_prq.cold.13 (STB_LOCAL)
ffffffff816768b0-ffffffff816769af: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:49
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81695bd7-ffffffff81695c47: intel_svm_enable_prq.cold.9 (STB_LOCAL)
ffffffff81695a20-ffffffff81695b1f: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:41
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816ce508-ffffffff816ce578: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff816ce320-ffffffff816ce41f: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:41
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f2335-ffffffff816f23a5: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff816f2160-ffffffff816f225f: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:30
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817aa854-ffffffff817aa8c4: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff817a9fb0-ffffffff817aa0d3: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:31
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81c0cf7f-ffffffff81c0cfef: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff817b6450-ffffffff817b6573: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:31
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81bff317-ffffffff81bff387: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff817996e0-ffffffff81799806: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:85
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81d0129f-ffffffff81d01341: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff81821bf0-ffffffff81821d53: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (0)
Location: drivers/iommu/intel/svm.c:85
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ec97c9-ffffffff81ec9865: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff81961da0-ffffffff81961f15: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81acaaf0)
Location: drivers/iommu/intel/svm.c:68
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81acaaf0-ffffffff81acad25: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b17640)
Location: drivers/iommu/intel/svm.c:66
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b17640-ffffffff81b17875: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b6cc30)
Location: drivers/iommu/intel/svm.c:64
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b6cc30-ffffffff81b6ce65: intel_svm_enable_prq (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:41
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816b7b25-ffffffff816b7b95: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff816b7950-ffffffff816b7a4f: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:41
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81695765-ffffffff816957d5: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff81695590-ffffffff8169568f: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:41
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816e5ff5-ffffffff816e6065: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff816e5e20-ffffffff816e5f1f: intel_svm_enable_prq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_svm_enable_prq(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-svm.c (0)
Location: drivers/iommu/intel-svm.c:41
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817006f5-ffffffff81700765: intel_svm_enable_prq.cold (STB_LOCAL)
ffffffff81700520-ffffffff8170061f: intel_svm_enable_prq (STB_GLOBAL)
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
