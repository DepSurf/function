# Function: <code>qi_check_fault</code>

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
In drivers/iommu/dmar.c (ffffffff8153499e)
Location: drivers/iommu/dmar.c:1126
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
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
In drivers/iommu/dmar.c (ffffffff8158938a)
Location: drivers/iommu/dmar.c:1144
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
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
In drivers/iommu/dmar.c (ffffffff815b6a4a)
Location: drivers/iommu/dmar.c:1145
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
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
In drivers/iommu/dmar.c (ffffffff815cc8a9)
Location: drivers/iommu/dmar.c:1154
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81633699)
Location: drivers/iommu/dmar.c:1157
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8166e843)
Location: drivers/iommu/dmar.c:1157
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168cd2e)
Location: drivers/iommu/dmar.c:1157
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816c4763)
Location: drivers/iommu/dmar.c:1146
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816e76b3)
Location: drivers/iommu/dmar.c:1156
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1162
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff8179c230-ffffffff8179c344: qi_check_fault (STB_LOCAL)
ffffffff8179eb32-ffffffff8179eb8b: qi_check_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1201
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff817a9f00-ffffffff817aa014: qi_check_fault (STB_LOCAL)
ffffffff81c0bf5d-ffffffff81c0bfb6: qi_check_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1265
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff8178cbc0-ffffffff8178cd91: qi_check_fault (STB_LOCAL)
ffffffff81bfd649-ffffffff81bfd7cf: qi_check_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1264
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff81814200-ffffffff818143d1: qi_check_fault (STB_LOCAL)
ffffffff81cfeb5f-ffffffff81cfece5: qi_check_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1260
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff81955060-ffffffff81955246: qi_check_fault (STB_LOCAL)
ffffffff81ec7369-ffffffff81ec74f2: qi_check_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abbd00)
Location: drivers/iommu/intel/dmar.c:1249
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff81abbd00-ffffffff81abc0a5: qi_check_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b08620)
Location: drivers/iommu/intel/dmar.c:1270
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff81b08620-ffffffff81b0899a: qi_check_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int qi_check_fault(struct intel_iommu *iommu, int index, int wait_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5c640)
Location: drivers/iommu/intel/dmar.c:1270
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
**Symbols:**

```
ffffffff81b5c640-ffffffff81b5c9ba: qi_check_fault (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816ad193)
Location: drivers/iommu/dmar.c:1156
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168aaf3)
Location: drivers/iommu/dmar.c:1156
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816db373)
Location: drivers/iommu/dmar.c:1156
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816f5943)
Location: drivers/iommu/dmar.c:1156
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:qi_submit_sync
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
