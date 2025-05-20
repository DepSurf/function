# Function: <code>xen_cleanmfnmap_pud</code>

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
In arch/x86/xen/mmu_pv.c (ffffffff820a6d64)
Location: arch/x86/xen/mmu_pv.c:1148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
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
In arch/x86/xen/mmu_pv.c (ffffffff826ad4af)
Location: arch/x86/xen/mmu_pv.c:1121
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
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
In arch/x86/xen/mmu_pv.c (ffffffff826d67ba)
Location: arch/x86/xen/mmu_pv.c:1150
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c703)
Location: arch/x86/xen/mmu_pv.c:1160
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3ba4)
Location: arch/x86/xen/mmu_pv.c:1160
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6c3e)
Location: arch/x86/xen/mmu_pv.c:1160
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_cleanmfnmap_pud(pud_t *pud, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82cccf76)
Location: arch/x86/xen/mmu_pv.c:1160
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
**Symbols:**

```
ffffffff82cccf76-ffffffff82ccd049: xen_cleanmfnmap_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_cleanmfnmap_pud(pud_t *pud, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8db2)
Location: arch/x86/xen/mmu_pv.c:1064
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
**Symbols:**

```
ffffffff82fb8db2-ffffffff82fb8e85: xen_cleanmfnmap_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_cleanmfnmap_pud(pud_t *pud, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c3307)
Location: arch/x86/xen/mmu_pv.c:1064
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
**Symbols:**

```
ffffffff831c3307-ffffffff831c34aa: xen_cleanmfnmap_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_cleanmfnmap_pud(pud_t *pud, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a3d41)
Location: arch/x86/xen/mmu_pv.c:1064
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
**Symbols:**

```
ffffffff832a3d41-ffffffff832a3ee4: xen_cleanmfnmap_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_cleanmfnmap_pud(pud_t *pud, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83452fca)
Location: arch/x86/xen/mmu_pv.c:1070
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
**Symbols:**

```
ffffffff83452fca-ffffffff83453182: xen_cleanmfnmap_pud (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff83e704f5)
Location: arch/x86/xen/mmu_pv.c:1070
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
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
In arch/x86/xen/mmu_pv.c (ffffffff83691375)
Location: arch/x86/xen/mmu_pv.c:1079
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
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
In arch/x86/xen/mmu_pv.c (ffffffff838c0e85)
Location: arch/x86/xen/mmu_pv.c:1079
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
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
In arch/x86/xen/mmu_pv.c (ffffffff82894c47)
Location: arch/x86/xen/mmu_pv.c:1160
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c3e)
Location: arch/x86/xen/mmu_pv.c:1160
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7c44)
Location: arch/x86/xen/mmu_pv.c:1160
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
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
</ul>
