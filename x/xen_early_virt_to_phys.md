# Function: <code>xen_early_virt_to_phys</code>

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
In arch/x86/xen/mmu.c (ffffffff81f62982)
Location: arch/x86/xen/mmu.c:2043
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
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
In arch/x86/xen/mmu.c (ffffffff81f8a57e)
Location: arch/x86/xen/mmu.c:2033
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
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
In arch/x86/xen/mmu.c (ffffffff81fc5978)
Location: arch/x86/xen/mmu.c:2033
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff820a683a)
Location: arch/x86/xen/mmu_pv.c:2012
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff826acf1e)
Location: arch/x86/xen/mmu_pv.c:1982
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6271)
Location: arch/x86/xen/mmu_pv.c:2014
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c1bc)
Location: arch/x86/xen/mmu_pv.c:2022
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff828a365b)
Location: arch/x86/xen/mmu_pv.c:2012
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6701)
Location: arch/x86/xen/mmu_pv.c:2012
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc2c2)
Location: arch/x86/xen/mmu_pv.c:2012
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff82ccc2c2-ffffffff82ccc441: xen_early_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8100)
Location: arch/x86/xen/mmu_pv.c:1812
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff82fb8100-ffffffff82fb827f: xen_early_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c2763)
Location: arch/x86/xen/mmu_pv.c:1811
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff831c2763-ffffffff831c28ea: xen_early_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a3153)
Location: arch/x86/xen/mmu_pv.c:1814
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff832a3153-ffffffff832a32f6: xen_early_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff834523c2)
Location: arch/x86/xen/mmu_pv.c:1837
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff834523c2-ffffffff83452571: xen_early_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f8f0)
Location: arch/x86/xen/mmu_pv.c:1837
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff83e6f8f0-ffffffff83e6fb76: xen_early_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff836906b0)
Location: arch/x86/xen/mmu_pv.c:1846
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff836906b0-ffffffff83690930: xen_early_virt_to_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t xen_early_virt_to_phys(long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff838c0180)
Location: arch/x86/xen/mmu_pv.c:1846
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff838c0180-ffffffff838c0400: xen_early_virt_to_phys (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff8289470a)
Location: arch/x86/xen/mmu_pv.c:2012
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7701)
Location: arch/x86/xen/mmu_pv.c:2012
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7707)
Location: arch/x86/xen/mmu_pv.c:2012
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
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
