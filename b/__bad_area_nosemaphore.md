# Function: <code>__bad_area_nosemaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106af90)
Location: arch/x86/mm/fault.c:763
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_nosemaphore
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_access_error
```
**Symbols:**

```
ffffffff8106af90-ffffffff8106b180: __bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106ad00)
Location: arch/x86/mm/fault.c:823
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106ad00-ffffffff8106aeb6: __bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e910)
Location: arch/x86/mm/fault.c:854
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106e910-ffffffff8106eac6: __bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e0a0)
Location: arch/x86/mm/fault.c:895
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106e0a0-ffffffff8106e249: __bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 *pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810730e0)
Location: arch/x86/mm/fault.c:871
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810730e0-ffffffff81073289: __bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 *pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:843
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81075aa0-ffffffff81075c0d: __bad_area_nosemaphore (STB_LOCAL)
ffffffff81076567-ffffffff810765c9: __bad_area_nosemaphore.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:901
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107b870-ffffffff8107ba22: __bad_area_nosemaphore (STB_LOCAL)
ffffffff8107cb7a-ffffffff8107cbe7: __bad_area_nosemaphore.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:866
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107f390-ffffffff8107f52c: __bad_area_nosemaphore (STB_LOCAL)
ffffffff81080414-ffffffff81080476: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:888
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81080420-ffffffff810805bc: __bad_area_nosemaphore (STB_LOCAL)
ffffffff810814be-ffffffff81081520: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:852
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81087490-ffffffff810875e8: __bad_area_nosemaphore (STB_LOCAL)
ffffffff81088428-ffffffff8108848d: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:801
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81087b40-ffffffff81087cd3: __bad_area_nosemaphore (STB_LOCAL)
ffffffff81bd9608-ffffffff81bd9671: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:795
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81088700-ffffffff81088882: __bad_area_nosemaphore (STB_LOCAL)
ffffffff81bcb57d-ffffffff81bcb5e1: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:800
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81097b30-ffffffff81097cba: __bad_area_nosemaphore (STB_LOCAL)
ffffffff81ca0c4f-ffffffff81ca0cb3: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:800
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810aa6d0-ffffffff810aa8a0: __bad_area_nosemaphore (STB_LOCAL)
ffffffff81e501dd-ffffffff81e50241: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c41c0)
Location: arch/x86/mm/fault.c:831
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810c41c0-ffffffff810c447f: __bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c7a00)
Location: arch/x86/mm/fault.c:811
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810c7a00-ffffffff810c7cbf: __bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810cfed0)
Location: arch/x86/mm/fault.c:802
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810cfed0-ffffffff810d018d: __bad_area_nosemaphore (STB_LOCAL)
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
In arch/powerpc/mm/fault.c (c000000000085f80)
Location: arch/powerpc/mm/fault.c:83
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:bad_access
  - arch/powerpc/mm/fault.c:bad_area
  - arch/powerpc/mm/fault.c:bad_area_nosemaphore
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:888
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107f420-ffffffff8107f5bc: __bad_area_nosemaphore (STB_LOCAL)
ffffffff810804be-ffffffff81080520: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:888
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8106e400-ffffffff8106e596: __bad_area_nosemaphore (STB_LOCAL)
ffffffff8106f40a-ffffffff8106f46c: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:888
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8107f3d0-ffffffff8107f56c: __bad_area_nosemaphore (STB_LOCAL)
ffffffff8108046e-ffffffff810804d0: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:888
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
  - arch/x86/mm/fault.c:bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810814c0-ffffffff8108165c: __bad_area_nosemaphore (STB_LOCAL)
ffffffff8108258e-ffffffff810825f0: __bad_area_nosemaphore.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address, si_code</code> ➡️ <code>regs, error_code, address, vma, si_code</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *pkey</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 *pkey</code> ➡️ <code>u32 pkey</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
