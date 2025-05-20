# Function: <code>amd_iommu_init_pci</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81fa9e7e)
Location: drivers/iommu/amd_iommu_init.c:1355
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
In drivers/iommu/amd_iommu_init.c (ffffffff81fd6955)
Location: drivers/iommu/amd_iommu_init.c:1560
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820129eb)
Location: drivers/iommu/amd_iommu_init.c:1680
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff820129eb-ffffffff820130e7: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820f5f4f)
Location: drivers/iommu/amd_iommu_init.c:1692
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff820f5f4f-ffffffff820f668f: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff826ff68e)
Location: drivers/iommu/amd_iommu_init.c:1837
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff826ff68e-ffffffff826ffdc5: amd_iommu_init_pci (STB_LOCAL)
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
In drivers/iommu/amd_iommu_init.c (ffffffff82729acd)
Location: drivers/iommu/amd_iommu_init.c:1838
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e2367)
Location: drivers/iommu/amd_iommu_init.c:1871
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fcc35)
Location: drivers/iommu/amd_iommu_init.c:1858
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82905c0a)
Location: drivers/iommu/amd_iommu_init.c:1878
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1aca2)
Location: drivers/iommu/amd/init.c:1865
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff82d1aca2-ffffffff82d1ad38: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83008da6)
Location: drivers/iommu/amd/init.c:1979
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff83008da6-ffffffff83008ee8: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832137f8)
Location: drivers/iommu/amd/init.c:1932
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff832137f8-ffffffff83213a18: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832fca81)
Location: drivers/iommu/amd/init.c:1946
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff832fca81-ffffffff832fccb6: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b5635)
Location: drivers/iommu/amd/init.c:1953
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff834b5635-ffffffff834b589a: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83ef1430)
Location: drivers/iommu/amd/init.c:2162
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff83ef1430-ffffffff83ef1764: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83717040)
Location: drivers/iommu/amd/init.c:2199
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff83717040-ffffffff8371737a: amd_iommu_init_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_iommu_init_pci();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8394aa90)
Location: drivers/iommu/amd/init.c:2195
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff8394aa90-ffffffff8394ad9c: amd_iommu_init_pci (STB_LOCAL)
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ed3f1)
Location: drivers/iommu/amd_iommu_init.c:1878
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e487e)
Location: drivers/iommu/amd_iommu_init.c:1878
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82900f2d)
Location: drivers/iommu/amd_iommu_init.c:1878
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82906c6c)
Location: drivers/iommu/amd_iommu_init.c:1878
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
