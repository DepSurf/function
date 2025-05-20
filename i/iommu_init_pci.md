# Function: <code>iommu_init_pci</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81fa9e92)
Location: drivers/iommu/amd_iommu_init.c:1226
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff81fd6969)
Location: drivers/iommu/amd_iommu_init.c:1431
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82012a1d)
Location: drivers/iommu/amd_iommu_init.c:1538
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff820f5f8e)
Location: drivers/iommu/amd_iommu_init.c:1549
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff826ff69f)
Location: drivers/iommu/amd_iommu_init.c:1694
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166c5fd)
Location: drivers/iommu/amd_iommu_init.c:1694
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff8166c5fd-ffffffff8166cbe8: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e1bf3)
Location: drivers/iommu/amd_iommu_init.c:1725
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff828e1bf3-ffffffff828e21e8: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828fb1a5)
Location: drivers/iommu/amd_iommu_init.c:1712
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff828fb1a5-ffffffff828fb7c7: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8290402e)
Location: drivers/iommu/amd_iommu_init.c:1732
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff8290402e-ffffffff82904691: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1a850)
Location: drivers/iommu/amd/init.c:1727
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff82d1a850-ffffffff82d1aca2: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83008a73)
Location: drivers/iommu/amd/init.c:1842
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff83008a73-ffffffff83008da6: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832132bc)
Location: drivers/iommu/amd/init.c:1796
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff832132bc-ffffffff832137f8: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832fc59c)
Location: drivers/iommu/amd/init.c:1807
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff832fc59c-ffffffff832fca81: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b5168)
Location: drivers/iommu/amd/init.c:1814
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff834b5168-ffffffff834b5635: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83ef0df0)
Location: drivers/iommu/amd/init.c:2008
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff83ef0df0-ffffffff83ef1418: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83716a30)
Location: drivers/iommu/amd/init.c:2043
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff83716a30-ffffffff83717028: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8394a4c0)
Location: drivers/iommu/amd/init.c:2057
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff8394a4c0-ffffffff8394aa7d: iommu_init_pci (STB_LOCAL)
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
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828eb815)
Location: drivers/iommu/amd_iommu_init.c:1732
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff828eb815-ffffffff828ebe78: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e2ca2)
Location: drivers/iommu/amd_iommu_init.c:1732
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff828e2ca2-ffffffff828e3305: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ff351)
Location: drivers/iommu/amd_iommu_init.c:1732
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff828ff351-ffffffff828ff9b4: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82905090)
Location: drivers/iommu/amd_iommu_init.c:1732
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff82905090-ffffffff829056f3: iommu_init_pci (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
