# Function: <code>lapic_assign_legacy_vector</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff826bd95c)
Location: arch/x86/kernel/apic/vector.c:657
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff8105c580-ffffffff8105c59e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff826e7711)
Location: arch/x86/kernel/apic/vector.c:668
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff8105f550-ffffffff8105f56e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8289e25a)
Location: arch/x86/kernel/apic/vector.c:659
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff810651c0-ffffffff810651de: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828b60eb)
Location: arch/x86/kernel/apic/vector.c:656
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff810688b0-ffffffff810688ce: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828b95ae)
Location: arch/x86/kernel/apic/vector.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff81069220-ffffffff8106923e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff82cde5b4)
Location: arch/x86/kernel/apic/vector.c:676
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff81070210-ffffffff8107022e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff82fca972)
Location: arch/x86/kernel/apic/vector.c:723
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff81071780-ffffffff8107179e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff831d52d1)
Location: arch/x86/kernel/apic/vector.c:731
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff81072280-ffffffff8107229e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff832b7e03)
Location: arch/x86/kernel/apic/vector.c:731
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff8107e130-ffffffff8107e14e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff83469aba)
Location: arch/x86/kernel/apic/vector.c:731
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff8108d760-ffffffff8108d788: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e78a)
Location: arch/x86/kernel/apic/vector.c:727
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff810a1e40-ffffffff810a1e68: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff836b202a)
Location: arch/x86/kernel/apic/vector.c:727
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff810a4e20-ffffffff810a4e48: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff838e24ea)
Location: arch/x86/kernel/apic/vector.c:738
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/vector.c:lapic_update_legacy_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff810abe70-ffffffff810abe98: lapic_assign_legacy_vector (STB_GLOBAL)
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
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828a75b5)
Location: arch/x86/kernel/apic/vector.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff81068d10-ffffffff81068d2e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8289f6b2)
Location: arch/x86/kernel/apic/vector.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff81059080-ffffffff8105909e: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828ba4c5)
Location: arch/x86/kernel/apic/vector.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff810691c0-ffffffff810691de: lapic_assign_legacy_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lapic_assign_legacy_vector(unsigned int irq, bool replace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828ba5db)
Location: arch/x86/kernel/apic/vector.c:667
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
Direct callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
**Symbols:**

```
ffffffff8106a8d0-ffffffff8106a8ee: lapic_assign_legacy_vector (STB_GLOBAL)
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
