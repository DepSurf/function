# Function: <code>iommu_alloc_root_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81538310)
Location: drivers/iommu/intel-iommu.c:1287
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81538310-ffffffff815383d7: iommu_alloc_root_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158ce00)
Location: drivers/iommu/intel-iommu.c:1294
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8158ce00-ffffffff8158cec6: iommu_alloc_root_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815ba680)
Location: drivers/iommu/intel-iommu.c:1308
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815ba680-ffffffff815ba73c: iommu_alloc_root_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cf5f0)
Location: drivers/iommu/intel-iommu.c:1313
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815cf5f0-ffffffff815cf696: iommu_alloc_root_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81636380)
Location: drivers/iommu/intel-iommu.c:1296
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81636380-ffffffff81636426: iommu_alloc_root_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81671820)
Location: drivers/iommu/intel-iommu.c:1298
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81671820-ffffffff816718c6: iommu_alloc_root_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1174
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816902b0-ffffffff81690311: iommu_alloc_root_entry (STB_LOCAL)
ffffffff8169395c-ffffffff81693976: iommu_alloc_root_entry.cold.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1179
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816c8450-ffffffff816c84b1: iommu_alloc_root_entry (STB_LOCAL)
ffffffff816cbf08-ffffffff816cbf22: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1190
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816eb400-ffffffff816eb461: iommu_alloc_root_entry (STB_LOCAL)
ffffffff816ef7ca-ffffffff816ef7e4: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1206
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817a24a0-ffffffff817a2536: iommu_alloc_root_entry (STB_LOCAL)
ffffffff817a6ddb-ffffffff817a6df6: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1289
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817af700-ffffffff817af796: iommu_alloc_root_entry (STB_LOCAL)
ffffffff81c0c5c3-ffffffff81c0c5de: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1308
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817926d0-ffffffff81792766: iommu_alloc_root_entry (STB_LOCAL)
ffffffff81bfddc7-ffffffff81bfdde2: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1312
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8181a370-ffffffff8181a406: iommu_alloc_root_entry (STB_LOCAL)
ffffffff81cff84f-ffffffff81cff86a: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1242
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8195abd0-ffffffff8195ac72: iommu_alloc_root_entry (STB_LOCAL)
ffffffff81ec7fe2-ffffffff81ec7ffd: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac5536)
Location: drivers/iommu/intel/iommu.c:1194
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b11f9e)
Location: drivers/iommu/intel/iommu.c:1193
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b65cf0)
Location: drivers/iommu/intel/iommu.c:1053
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
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
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1190
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816b0d30-ffffffff816b0d91: iommu_alloc_root_entry (STB_LOCAL)
ffffffff816b4fba-ffffffff816b4fd4: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1190
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168e830-ffffffff8168e891: iommu_alloc_root_entry (STB_LOCAL)
ffffffff81692bfa-ffffffff81692c14: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1190
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816df0c0-ffffffff816df121: iommu_alloc_root_entry (STB_LOCAL)
ffffffff816e348a-ffffffff816e34a4: iommu_alloc_root_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iommu_alloc_root_entry(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1190
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f96d0-ffffffff816f9731: iommu_alloc_root_entry (STB_LOCAL)
ffffffff816fdb1a-ffffffff816fdb34: iommu_alloc_root_entry.cold (STB_LOCAL)
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
