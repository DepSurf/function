# Function: <code>amd_iommu_activate_guest_mode</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dfa30)
Location: drivers/iommu/amd_iommu.c:4405
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816dfa30-ffffffff816dfa9a: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81797740)
Location: drivers/iommu/amd/iommu.c:3830
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81797740-ffffffff817977b5: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5eb0)
Location: drivers/iommu/amd/iommu.c:3882
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff817a5eb0-ffffffff817a5f25: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787ab0)
Location: drivers/iommu/amd/iommu.c:3248
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81787ab0-ffffffff81787b25: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180f390)
Location: drivers/iommu/amd/iommu.c:3316
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff8180f390-ffffffff8180f405: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194ff50)
Location: drivers/iommu/amd/iommu.c:3342
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff8194ff50-ffffffff8194ffe9: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab4f60)
Location: drivers/iommu/amd/iommu.c:3495
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81ab4f60-ffffffff81ab5006: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afef30)
Location: drivers/iommu/amd/iommu.c:3533
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81afef30-ffffffff81afefb5: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b53940)
Location: drivers/iommu/amd/iommu.c:3584
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81b53940-ffffffff81b539fc: amd_iommu_activate_guest_mode (STB_GLOBAL)
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
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a5480)
Location: drivers/iommu/amd_iommu.c:4405
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816a5480-ffffffff816a54ea: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682e70)
Location: drivers/iommu/amd_iommu.c:4405
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81682e70-ffffffff81682eda: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d36f0)
Location: drivers/iommu/amd_iommu.c:4405
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816d36f0-ffffffff816d375a: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int amd_iommu_activate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eddf0)
Location: drivers/iommu/amd_iommu.c:4405
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816eddf0-ffffffff816ede5a: amd_iommu_activate_guest_mode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
