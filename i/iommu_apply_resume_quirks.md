# Function: <code>iommu_apply_resume_quirks</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81532c99)
Location: drivers/iommu/amd_iommu_init.c:1607
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff815874b9)
Location: drivers/iommu/amd_iommu_init.c:1822
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff815b4bb9)
Location: drivers/iommu/amd_iommu_init.c:1944
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff815caa2a)
Location: drivers/iommu/amd_iommu_init.c:1964
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff816317ea)
Location: drivers/iommu/amd_iommu_init.c:2100
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166c369)
Location: drivers/iommu/amd_iommu_init.c:2101
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff8168ac79)
Location: drivers/iommu/amd_iommu_init.c:2134
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff816c26b9)
Location: drivers/iommu/amd_iommu_init.c:2210
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff816e55d9)
Location: drivers/iommu/amd_iommu_init.c:2230
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b440)
Location: drivers/iommu/amd/init.c:2200
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff8179b440-ffffffff8179b5ea: iommu_apply_resume_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9880)
Location: drivers/iommu/amd/init.c:2404
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff817a9880-ffffffff817a9a2a: iommu_apply_resume_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b580)
Location: drivers/iommu/amd/init.c:2357
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff8178b580-ffffffff8178b72a: iommu_apply_resume_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81812180)
Location: drivers/iommu/amd/init.c:2381
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff81812180-ffffffff8181239e: iommu_apply_resume_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81953080)
Location: drivers/iommu/amd/init.c:2395
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff81953080-ffffffff819532b1: iommu_apply_resume_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab88c0)
Location: drivers/iommu/amd/init.c:2620
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff81ab88c0-ffffffff81ab8af1: iommu_apply_resume_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b04c30)
Location: drivers/iommu/amd/init.c:2658
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff81b04c30-ffffffff81b04e61: iommu_apply_resume_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_apply_resume_quirks(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58940)
Location: drivers/iommu/amd/init.c:2678
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
```
**Symbols:**

```
ffffffff81b58940-ffffffff81b58b71: iommu_apply_resume_quirks (STB_LOCAL)
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
In drivers/iommu/amd_iommu_init.c (ffffffff816ab0b9)
Location: drivers/iommu/amd_iommu_init.c:2230
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff81688a19)
Location: drivers/iommu/amd_iommu_init.c:2230
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff816d9299)
Location: drivers/iommu/amd_iommu_init.c:2230
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff816f3849)
Location: drivers/iommu/amd_iommu_init.c:2230
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
