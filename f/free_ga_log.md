# Function: <code>free_ga_log</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff817860fc)
Location: drivers/iommu/amd_iommu_init.c:683
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff817860fc-ffffffff81786132: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815cac90)
Location: drivers/iommu/amd_iommu_init.c:692
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff815cac90-ffffffff815cacc6: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81631a50)
Location: drivers/iommu/amd_iommu_init.c:737
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff81631a50-ffffffff81631a86: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166c5c0)
Location: drivers/iommu/amd_iommu_init.c:737
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff8166c5c0-ffffffff8166c5f6: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168aed0)
Location: drivers/iommu/amd_iommu_init.c:740
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff8168aed0-ffffffff8168af06: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c290a)
Location: drivers/iommu/amd_iommu_init.c:728
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816c290a-ffffffff816c2940: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e5812)
Location: drivers/iommu/amd_iommu_init.c:729
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816e5812-ffffffff816e5848: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179baae)
Location: drivers/iommu/amd/init.c:729
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:iommu_init_ga_log
```
**Symbols:**

```
ffffffff8179baae-ffffffff8179baf5: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81c0b8ce)
Location: drivers/iommu/amd/init.c:783
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:iommu_init_ga_log
```
**Symbols:**

```
ffffffff81c0b8ce-ffffffff81c0b8fa: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81bfd290)
Location: drivers/iommu/amd/init.c:779
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81bfd290-ffffffff81bfd2bc: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81cfe533)
Location: drivers/iommu/amd/init.c:806
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81cfe533-ffffffff81cfe55f: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ec6d26)
Location: drivers/iommu/amd/init.c:810
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81ec6d26-ffffffff81ec6d5a: free_ga_log (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff83ef3ecb)
Location: drivers/iommu/amd/init.c:892
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd/init.c (ffffffff83719a7b)
Location: drivers/iommu/amd/init.c:927
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd/init.c (ffffffff8394d57b)
Location: drivers/iommu/amd/init.c:942
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
<summary>In <code>aws</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816ab2f2)
Location: drivers/iommu/amd_iommu_init.c:729
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816ab2f2-ffffffff816ab328: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81688c52)
Location: drivers/iommu/amd_iommu_init.c:729
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81688c52-ffffffff81688c88: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d94d2)
Location: drivers/iommu/amd_iommu_init.c:729
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816d94d2-ffffffff816d9508: free_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f3a82)
Location: drivers/iommu/amd_iommu_init.c:729
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff816f3a82-ffffffff816f3ab8: free_ga_log (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
