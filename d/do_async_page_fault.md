# Function: <code>do_async_page_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063ec0)
Location: arch/x86/kernel/kvm.c:258
Inline: True
```
**Symbols:**

```
ffffffff81063ec0-ffffffff81063f2b: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063ae0)
Location: arch/x86/kernel/kvm.c:259
Inline: True
```
**Symbols:**

```
ffffffff81063ae0-ffffffff81063b4b: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066f90)
Location: arch/x86/kernel/kvm.c:258
Inline: True
```
**Symbols:**

```
ffffffff81066f90-ffffffff81066ff1: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066260)
Location: arch/x86/kernel/kvm.c:260
Inline: True
```
**Symbols:**

```
ffffffff81066260-ffffffff810662c1: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106a450)
Location: arch/x86/kernel/kvm.c:267
Inline: True
```
**Symbols:**

```
ffffffff8106a450-ffffffff8106a4c3: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106d0b0)
Location: arch/x86/kernel/kvm.c:267
Inline: True
```
**Symbols:**

```
ffffffff8106d0b0-ffffffff8106d123: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81073280)
Location: arch/x86/kernel/kvm.c:258
Inline: True
```
**Symbols:**

```
ffffffff81073280-ffffffff810732f3: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076e20)
Location: arch/x86/kernel/kvm.c:245
Inline: True
```
**Symbols:**

```
ffffffff81076e20-ffffffff81076e8c: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81077e70)
Location: arch/x86/kernel/kvm.c:245
Inline: True
```
**Symbols:**

```
ffffffff81077e70-ffffffff81077edc: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076e70)
Location: arch/x86/kernel/kvm.c:245
Inline: True
```
**Symbols:**

```
ffffffff81076e70-ffffffff81076edc: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066ec0)
Location: arch/x86/kernel/kvm.c:245
Inline: True
```
**Symbols:**

```
ffffffff81066ec0-ffffffff81066f83: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076e20)
Location: arch/x86/kernel/kvm.c:245
Inline: True
```
**Symbols:**

```
ffffffff81076e20-ffffffff81076e8c: do_async_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void do_async_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81078e90)
Location: arch/x86/kernel/kvm.c:245
Inline: True
```
**Symbols:**

```
ffffffff81078e90-ffffffff81078efc: do_async_page_fault (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
