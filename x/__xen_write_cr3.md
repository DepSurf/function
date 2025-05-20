# Function: <code>__xen_write_cr3</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810208d0)
Location: arch/x86/xen/mmu.c:1421
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_write_cr3_init
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
**Symbols:**

```
ffffffff810208d0-ffffffff81020a44: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810208d0)
Location: arch/x86/xen/mmu.c:1422
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_write_cr3_init
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
```
**Symbols:**

```
ffffffff810208d0-ffffffff81020a39: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81021040)
Location: arch/x86/xen/mmu.c:1422
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_write_cr3_init
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81021040-ffffffff810211a9: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020e40)
Location: arch/x86/xen/mmu_pv.c:1411
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81020e40-ffffffff81020f9f: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810219e0)
Location: arch/x86/xen/mmu_pv.c:1369
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff810219e0-ffffffff81021b42: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810221f0)
Location: arch/x86/xen/mmu_pv.c:1396
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff810221f0-ffffffff81022355: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021e60)
Location: arch/x86/xen/mmu_pv.c:1404
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81021e60-ffffffff81021fc5: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:1394
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81025610-ffffffff8102576a: __xen_write_cr3 (STB_LOCAL)
ffffffff81027c91-ffffffff81027ca6: __xen_write_cr3.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025bf0)
Location: arch/x86/xen/mmu_pv.c:1394
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81025bf0-ffffffff81025d4c: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027f50)
Location: arch/x86/xen/mmu_pv.c:1394
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81027f50-ffffffff810280ac: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027bf0)
Location: arch/x86/xen/mmu_pv.c:1296
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81027bf0-ffffffff81027d2d: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a450)
Location: arch/x86/xen/mmu_pv.c:1295
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff8102a450-ffffffff8102a58d: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102ea60)
Location: arch/x86/xen/mmu_pv.c:1295
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff8102ea60-ffffffff8102eb9a: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81033c40)
Location: arch/x86/xen/mmu_pv.c:1309
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81033c40-ffffffff81033dcb: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103b6b0)
Location: arch/x86/xen/mmu_pv.c:1309
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff8103b6b0-ffffffff8103b83b: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103b790)
Location: arch/x86/xen/mmu_pv.c:1318
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff8103b790-ffffffff8103b91b: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81041c50)
Location: arch/x86/xen/mmu_pv.c:1318
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81041c50-ffffffff81041ddb: __xen_write_cr3 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025d50)
Location: arch/x86/xen/mmu_pv.c:1394
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81025d50-ffffffff81025eac: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025bb0)
Location: arch/x86/xen/mmu_pv.c:1394
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff81025bb0-ffffffff81025d0c: __xen_write_cr3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __xen_write_cr3(bool kernel, long unsigned int cr3);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810266b0)
Location: arch/x86/xen/mmu_pv.c:1394
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_write_cr3_init
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
```
**Symbols:**

```
ffffffff810266b0-ffffffff8102682d: __xen_write_cr3 (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
