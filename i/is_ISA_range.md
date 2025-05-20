# Function: <code>is_ISA_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 s, u64 e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81033210)
Location: arch/x86/include/asm/e820.h:60
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/e820.h:60
Inline: True
```
**Symbols:**

```
ffffffff81033210-ffffffff8103322c: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 s, u64 e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff810323e0)
Location: arch/x86/include/asm/e820.h:60
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/e820.h:60
Inline: True
```
**Symbols:**

```
ffffffff810323e0-ffffffff810323fc: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 s, u64 e);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81032060)
Location: arch/x86/include/asm/e820.h:66
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/e820.h:66
Inline: True
```
**Symbols:**

```
ffffffff81032060-ffffffff8103207c: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff810302a0)
Location: arch/x86/include/asm/e820/api.h:46
Inline: False
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/e820/api.h:46
Inline: True
```
**Symbols:**

```
ffffffff810302a0-ffffffff810302bc: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81032630)
Location: arch/x86/include/asm/e820/api.h:49
Inline: False
```
**Symbols:**

```
ffffffff81032630-ffffffff8103264c: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81033950)
Location: arch/x86/include/asm/e820/api.h:49
Inline: False
```
**Symbols:**

```
ffffffff81033950-ffffffff81033967: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81034cb0)
Location: arch/x86/include/asm/e820/api.h:49
Inline: False
```
**Symbols:**

```
ffffffff81034cb0-ffffffff81034cc7: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81036c10)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
**Symbols:**

```
ffffffff81036c10-ffffffff81036c27: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff810373e0)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106cf85)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff810373e0-ffffffff810373f7: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81039290)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074335)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff81039290-ffffffff810392a7: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81039b50)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074e95)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff81039b50-ffffffff81039b67: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff8103b620)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075945)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff8103b620-ffffffff8103b637: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81041080)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082e15)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff81041080-ffffffff81041097: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81048c00)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092b85)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff81048c00-ffffffff81048c21: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81053a20)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7d55)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff81053a20-ffffffff81053a41: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81054a00)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810aafc5)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff81054a00-ffffffff81054a21: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff8105bc40)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b1f65)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff8105bc40-ffffffff8105bc61: is_ISA_range (STB_LOCAL)
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
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81037540)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
**Symbols:**

```
ffffffff81037540-ffffffff81037557: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff81026f20)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
**Symbols:**

```
ffffffff81026f20-ffffffff81026f37: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff810373a0)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
**Symbols:**

```
ffffffff810373a0-ffffffff810373b7: is_ISA_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool is_ISA_range(u64 start, u64 end);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/x86_init.c (ffffffff810383a0)
Location: arch/x86/include/asm/e820/api.h:50
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e645)
Location: arch/x86/include/asm/e820/api.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_is_untracked_pat_range
```
**Symbols:**

```
ffffffff810383a0-ffffffff810383b7: is_ISA_range (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 start</code>
</li>
<li>
<b>Param added. </b>
<code>u64 end</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 s</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 e</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
