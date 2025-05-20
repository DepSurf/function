# Function: <code>update_intr_gate</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff826af9ab)
Location: arch/x86/kernel/idt.c:358
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff826af9ab-ffffffff826af9cb: update_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff826d90b1)
Location: arch/x86/kernel/idt.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff826d90b1-ffffffff826d90d1: update_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8288f495)
Location: arch/x86/kernel/idt.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff8288f495-ffffffff8288f4b5: update_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff828a69b8)
Location: arch/x86/kernel/idt.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff828a69b8-ffffffff828a69d7: update_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff828a99e7)
Location: arch/x86/kernel/idt.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff828a99e7-ffffffff828a9a06: update_intr_gate (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff828979f7)
Location: arch/x86/kernel/idt.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff828979f7-ffffffff82897a16: update_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8288fd21)
Location: arch/x86/kernel/idt.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff8288fd21-ffffffff8288fd40: update_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff828aa9e7)
Location: arch/x86/kernel/idt.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff828aa9e7-ffffffff828aaa06: update_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff828aa9f7)
Location: arch/x86/kernel/idt.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apf_trap_init
```
**Symbols:**

```
ffffffff828aa9f7-ffffffff828aaa16: update_intr_gate (STB_GLOBAL)
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
