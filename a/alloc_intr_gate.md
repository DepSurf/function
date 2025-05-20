# Function: <code>alloc_intr_gate</code>

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
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102e0c0)
Location: arch/x86/kernel/idt.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102e0c0-ffffffff8102e0e9: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102f140)
Location: arch/x86/kernel/idt.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102f140-ffffffff8102f169: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810303d0)
Location: arch/x86/kernel/idt.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff810303d0-ffffffff810303f9: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810321b0)
Location: arch/x86/kernel/idt.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
```
**Symbols:**

```
ffffffff810321b0-ffffffff810321d8: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032a70)
Location: arch/x86/kernel/idt.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
```
**Symbols:**

```
ffffffff81032a70-ffffffff81032a98: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82ccf1a3)
Location: arch/x86/kernel/idt.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff82ccf1a3-ffffffff82ccf1da: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff82fbb069)
Location: arch/x86/kernel/idt.c:343
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff82fbb069-ffffffff82fbb0a0: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff831c58e1)
Location: arch/x86/kernel/idt.c:343
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff831c58e1-ffffffff831c5918: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff832a6632)
Location: arch/x86/kernel/idt.c:326
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff832a6632-ffffffff832a6698: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83455840)
Location: arch/x86/kernel/idt.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff83455840-ffffffff834558bb: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83e73790)
Location: arch/x86/kernel/idt.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff83e73790-ffffffff83e7380e: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff83695250)
Location: arch/x86/kernel/idt.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff83695250-ffffffff836952ce: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff838c5190)
Location: arch/x86/kernel/idt.c:340
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
**Symbols:**

```
ffffffff838c5190-ffffffff838c520e: alloc_intr_gate (STB_GLOBAL)
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
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032bd0)
Location: arch/x86/kernel/idt.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
```
**Symbols:**

```
ffffffff81032bd0-ffffffff81032bf8: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81022510)
Location: arch/x86/kernel/idt.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
```
**Symbols:**

```
ffffffff81022510-ffffffff81022538: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032a30)
Location: arch/x86/kernel/idt.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81032a30-ffffffff81032a58: alloc_intr_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void alloc_intr_gate(unsigned int n, const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81033990)
Location: arch/x86/kernel/idt.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/acrn.c:acrn_init_platform
```
**Symbols:**

```
ffffffff81033990-ffffffff810339b8: alloc_intr_gate (STB_GLOBAL)
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
