# Function: <code>iommu_init_msi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81532780)
Location: drivers/iommu/amd_iommu_init.c:1412
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff81532780-ffffffff81532844: iommu_init_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81586f60)
Location: drivers/iommu/amd_iommu_init.c:1627
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff81586f60-ffffffff81587024: iommu_init_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b46b0)
Location: drivers/iommu/amd_iommu_init.c:1747
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff815b46b0-ffffffff815b47cb: iommu_init_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca410)
Location: drivers/iommu/amd_iommu_init.c:1759
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff815ca410-ffffffff815ca524: iommu_init_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630df0)
Location: drivers/iommu/amd_iommu_init.c:1904
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff81630df0-ffffffff81630f04: iommu_init_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bcb0)
Location: drivers/iommu/amd_iommu_init.c:1905
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff8166bcb0-ffffffff8166bdc4: iommu_init_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a530)
Location: drivers/iommu/amd_iommu_init.c:1938
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff8168a530-ffffffff8168a64f: iommu_init_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2009
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816c1ee0-ffffffff816c2073: iommu_init_msi (STB_LOCAL)
ffffffff816c2940-ffffffff816c295f: iommu_init_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2029
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816e4e00-ffffffff816e4f93: iommu_init_msi (STB_LOCAL)
ffffffff816e5848-ffffffff816e5867: iommu_init_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b29c)
Location: drivers/iommu/amd/init.c:2016
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2029
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816aa8e0-ffffffff816aaa73: iommu_init_msi (STB_LOCAL)
ffffffff816ab328-ffffffff816ab347: iommu_init_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2029
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff81688420-ffffffff816885b3: iommu_init_msi (STB_LOCAL)
ffffffff81688c99-ffffffff81688cb8: iommu_init_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2029
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816d8ac0-ffffffff816d8c53: iommu_init_msi (STB_LOCAL)
ffffffff816d9508-ffffffff816d9527: iommu_init_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iommu_init_msi(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2029
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816f3070-ffffffff816f3203: iommu_init_msi (STB_LOCAL)
ffffffff816f3ab8-ffffffff816f3ad7: iommu_init_msi.cold (STB_LOCAL)
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
