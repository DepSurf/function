# Function: <code>xen_cleanmfnmap_p4d</code>

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
In arch/x86/xen/mmu_pv.c (ffffffff820a6d53)
Location: arch/x86/xen/mmu_pv.c:1170
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
In arch/x86/xen/mmu_pv.c (ffffffff826ad497)
Location: arch/x86/xen/mmu_pv.c:1143
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6770)
Location: arch/x86/xen/mmu_pv.c:1172
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c6b9)
Location: arch/x86/xen/mmu_pv.c:1182
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3b66)
Location: arch/x86/xen/mmu_pv.c:1182
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6c00)
Location: arch/x86/xen/mmu_pv.c:1182
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
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccd049)
Location: arch/x86/xen/mmu_pv.c:1182
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
```
**Symbols:**

```
ffffffff82ccd049-ffffffff82ccd0be: xen_cleanmfnmap_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8e85)
Location: arch/x86/xen/mmu_pv.c:1086
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
```
**Symbols:**

```
ffffffff82fb8e85-ffffffff82fb8efa: xen_cleanmfnmap_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c34aa)
Location: arch/x86/xen/mmu_pv.c:1086
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff831c34aa-ffffffff831c3536: xen_cleanmfnmap_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a3ee4)
Location: arch/x86/xen/mmu_pv.c:1086
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff832a3ee4-ffffffff832a3f70: xen_cleanmfnmap_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83453182)
Location: arch/x86/xen/mmu_pv.c:1092
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff83453182-ffffffff83453216: xen_cleanmfnmap_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83e70490)
Location: arch/x86/xen/mmu_pv.c:1092
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff83e70490-ffffffff83e707e0: xen_cleanmfnmap_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83691310)
Location: arch/x86/xen/mmu_pv.c:1101
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff83691310-ffffffff8369165a: xen_cleanmfnmap_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_cleanmfnmap_p4d(p4d_t *p4d, bool unpin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff838c0e20)
Location: arch/x86/xen/mmu_pv.c:1101
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff838c0e20-ffffffff838c116a: xen_cleanmfnmap_p4d (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff82894c09)
Location: arch/x86/xen/mmu_pv.c:1182
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7c00)
Location: arch/x86/xen/mmu_pv.c:1182
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7c06)
Location: arch/x86/xen/mmu_pv.c:1182
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
