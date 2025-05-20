# Function: <code>init_one_iommu</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff820a120a)
Location: arch/x86/events/amd/iommu.c:419
Inline: True
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
In arch/x86/events/amd/iommu.c (ffffffff826a72e9)
Location: arch/x86/events/amd/iommu.c:419
Inline: True
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
In arch/x86/events/amd/iommu.c (ffffffff826d0497)
Location: arch/x86/events/amd/iommu.c:419
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
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
In arch/x86/events/amd/iommu.c (ffffffff82886556)
Location: arch/x86/events/amd/iommu.c:419
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
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
In arch/x86/events/amd/iommu.c (ffffffff8289d4b0)
Location: arch/x86/events/amd/iommu.c:412
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
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
In arch/x86/events/amd/iommu.c (ffffffff828a051f)
Location: arch/x86/events/amd/iommu.c:412
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff82cc66c8)
Location: arch/x86/events/amd/iommu.c:412
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff82cc66c8-ffffffff82cc6879: init_one_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff82fb20e5)
Location: arch/x86/events/amd/iommu.c:412
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff82fb20e5-ffffffff82fb2296: init_one_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff831bc2bc)
Location: arch/x86/events/amd/iommu.c:418
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff831bc2bc-ffffffff831bc46d: init_one_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8329c56f)
Location: arch/x86/events/amd/iommu.c:418
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff8329c56f-ffffffff8329c720: init_one_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8344b02b)
Location: arch/x86/events/amd/iommu.c:418
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff8344b02b-ffffffff8344b1c9: init_one_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff83e65bf0)
Location: arch/x86/events/amd/iommu.c:418
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff83e65bf0-ffffffff83e65db6: init_one_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff83686270)
Location: arch/x86/events/amd/iommu.c:418
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff83686270-ffffffff83686436: init_one_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_one_iommu(unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff838b5400)
Location: arch/x86/events/amd/iommu.c:418
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
**Symbols:**

```
ffffffff838b5400-ffffffff838b55f5: init_one_iommu (STB_LOCAL)
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
In arch/x86/events/amd/iommu.c (ffffffff8288e51f)
Location: arch/x86/events/amd/iommu.c:412
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
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
In arch/x86/events/amd/iommu.c (ffffffff8288c485)
Location: arch/x86/events/amd/iommu.c:412
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
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
In arch/x86/events/amd/iommu.c (ffffffff828a151f)
Location: arch/x86/events/amd/iommu.c:412
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
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
In arch/x86/events/amd/iommu.c (ffffffff828a1533)
Location: arch/x86/events/amd/iommu.c:412
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
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
