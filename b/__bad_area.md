# Function: <code>__bad_area</code>

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
In arch/x86/mm/fault.c (ffffffff8106b1a6)
Location: arch/x86/mm/fault.c:826
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_access_error
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
In arch/x86/mm/fault.c (ffffffff8106af5d)
Location: arch/x86/mm/fault.c:892
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff8106eb6d)
Location: arch/x86/mm/fault.c:923
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff8106e2ed)
Location: arch/x86/mm/fault.c:964
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, int si_code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81073406)
Location: arch/x86/mm/fault.c:939
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
**Symbols:**

```
ffffffff810732b0-ffffffff8107334b: __bad_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, int si_code);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81075d85)
Location: arch/x86/mm/fault.c:911
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
**Symbols:**

```
ffffffff81075c30-ffffffff81075cc9: __bad_area (STB_LOCAL)
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
In arch/x86/mm/fault.c (ffffffff8107bb62)
Location: arch/x86/mm/fault.c:958
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff8107f5d0)
Location: arch/x86/mm/fault.c:923
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff81080660)
Location: arch/x86/mm/fault.c:945
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff81087690)
Location: arch/x86/mm/fault.c:911
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087d00)
Location: arch/x86/mm/fault.c:857
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
**Symbols:**

```
ffffffff81087d00-ffffffff81087d7d: __bad_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810888b0)
Location: arch/x86/mm/fault.c:853
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
**Symbols:**

```
ffffffff810888b0-ffffffff8108892a: __bad_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81097ce0)
Location: arch/x86/mm/fault.c:859
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
**Symbols:**

```
ffffffff81097ce0-ffffffff81097d59: __bad_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810aa8d0)
Location: arch/x86/mm/fault.c:859
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
**Symbols:**

```
ffffffff810aa8d0-ffffffff810aa955: __bad_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c4580)
Location: arch/x86/mm/fault.c:890
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
**Symbols:**

```
ffffffff810c4580-ffffffff810c4605: __bad_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c7dc0)
Location: arch/x86/mm/fault.c:870
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
**Symbols:**

```
ffffffff810c7dc0-ffffffff810c7e48: __bad_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bad_area(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810d0290)
Location: arch/x86/mm/fault.c:861
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
```
**Symbols:**

```
ffffffff810d0290-ffffffff810d0318: __bad_area (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/fault.c (c000000000085f64)
Location: arch/powerpc/mm/fault.c:103
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:bad_access
  - arch/powerpc/mm/fault.c:bad_area
```
</details>
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
In arch/x86/mm/fault.c (ffffffff8107f660)
Location: arch/x86/mm/fault.c:945
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff8106e6d0)
Location: arch/x86/mm/fault.c:945
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff8107f610)
Location: arch/x86/mm/fault.c:945
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
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
In arch/x86/mm/fault.c (ffffffff81081700)
Location: arch/x86/mm/fault.c:945
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
