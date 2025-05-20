# Function: <code>native_safe_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063a69)
Location: arch/x86/include/asm/irqflags.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff810645e0)
Location: arch/x86/include/asm/irqflags.h:47
Inline: False
```
**Symbols:**

```
ffffffff810645e0-ffffffff810645e8: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81063639)
Location: arch/x86/include/asm/irqflags.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064230)
Location: arch/x86/include/asm/irqflags.h:47
Inline: False
```
**Symbols:**

```
ffffffff81064230-ffffffff81064238: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81066af5)
Location: arch/x86/include/asm/irqflags.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff818d3d60)
Location: arch/x86/include/asm/irqflags.h:51
Inline: False
```
**Symbols:**

```
ffffffff818d3d60-ffffffff818d3d68: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81065e00)
Location: arch/x86/include/asm/irqflags.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff8190aec0)
Location: arch/x86/include/asm/irqflags.h:51
Inline: False
```
**Symbols:**

```
ffffffff8190aec0-ffffffff8190aec8: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106a3f4)
Location: arch/x86/include/asm/irqflags.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81995230)
Location: arch/x86/include/asm/irqflags.h:52
Inline: False
```
**Symbols:**

```
ffffffff81995230-ffffffff81995238: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8106d064)
Location: arch/x86/include/asm/irqflags.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff819f1790)
Location: arch/x86/include/asm/irqflags.h:55
Inline: False
```
**Symbols:**

```
ffffffff819f1790-ffffffff819f1798: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81073234)
Location: arch/x86/include/asm/irqflags.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a2cc30)
Location: arch/x86/include/asm/irqflags.h:55
Inline: False
```
**Symbols:**

```
ffffffff81a2cc30-ffffffff81a2cc38: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076d6a)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a9cdb0)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81a9cdb0-ffffffff81a9cdbf: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81077dba)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81ad4600)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81ad4600-ffffffff81ad460f: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81bcc660)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81bcc660-ffffffff81bcc66f: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void native_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81c45210)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81c45210-ffffffff81c4521f: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void native_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81c38490)
Location: arch/x86/include/asm/irqflags.h:48
Inline: False
```
**Symbols:**

```
ffffffff81c38490-ffffffff81c3849f: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void native_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81d56d40)
Location: arch/x86/include/asm/irqflags.h:48
Inline: False
```
**Symbols:**

```
ffffffff81d56d40-ffffffff81d56d4c: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void native_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81f29000)
Location: arch/x86/include/asm/irqflags.h:48
Inline: False
```
**Symbols:**

```
ffffffff81f29000-ffffffff81f29010: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void native_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff820d4ce0)
Location: arch/x86/include/asm/irqflags.h:48
Inline: False
```
**Symbols:**

```
ffffffff820d4ce0-ffffffff820d4cf0: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff82141030)
Location: arch/x86/include/asm/irqflags.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_safe_halt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff82222e50)
Location: arch/x86/include/asm/irqflags.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:pv_native_safe_halt
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076dba)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a73470)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81a73470-ffffffff81a7347f: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81a2f45b)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/kernel/kvm.c (ffffffff81066e0e)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In drivers/acpi/processor_idle.c (ffffffff815efa6d)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff81a2faf0-ffffffff81a2faff: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81076d6a)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81adf880)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81adf880-ffffffff81adf88f: native_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_safe_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81078dc7)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In arch/x86/kernel/paravirt.c (ffffffff81aec050)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81aec050-ffffffff81aec05f: native_safe_halt (STB_LOCAL)
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
