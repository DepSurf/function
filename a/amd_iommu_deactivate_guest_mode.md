# Function: <code>amd_iommu_deactivate_guest_mode</code>

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
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dfaa0)
Location: drivers/iommu/amd_iommu.c:4428
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816dfaa0-ffffffff816dfb36: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817977c0)
Location: drivers/iommu/amd/iommu.c:3857
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff817977c0-ffffffff81797853: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5f30)
Location: drivers/iommu/amd/iommu.c:3909
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff817a5f30-ffffffff817a5fc4: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787b30)
Location: drivers/iommu/amd/iommu.c:3275
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81787b30-ffffffff81787bc4: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3343
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81cfe150-ffffffff81cfe174: amd_iommu_deactivate_guest_mode.cold (STB_LOCAL)
ffffffff8180f410-ffffffff8180f4d6: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3369
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81ec6a5f-ffffffff81ec6a83: amd_iommu_deactivate_guest_mode.cold (STB_LOCAL)
ffffffff8194fff0-ffffffff819500da: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3522
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff82096e75-ffffffff82096e99: amd_iommu_deactivate_guest_mode.cold (STB_LOCAL)
ffffffff81ab5020-ffffffff81ab5119: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3559
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff82117c31-ffffffff82117c4e: amd_iommu_deactivate_guest_mode.cold (STB_LOCAL)
ffffffff81aff090-ffffffff81aff186: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b524b0)
Location: drivers/iommu/amd/iommu.c:3610
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81b524b0-ffffffff81b52571: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
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
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a54f0)
Location: drivers/iommu/amd_iommu.c:4428
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816a54f0-ffffffff816a5586: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682ee0)
Location: drivers/iommu/amd_iommu.c:4428
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff81682ee0-ffffffff81682f76: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3760)
Location: drivers/iommu/amd_iommu.c:4428
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816d3760-ffffffff816d37f6: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ede60)
Location: drivers/iommu/amd_iommu.c:4428
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
**Symbols:**

```
ffffffff816ede60-ffffffff816edef6: amd_iommu_deactivate_guest_mode (STB_GLOBAL)
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
