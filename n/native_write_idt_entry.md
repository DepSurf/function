# Function: <code>native_write_idt_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c3a4)
Location: arch/x86/include/asm/desc.h:119
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
```
```
In arch/x86/kernel/paravirt.c (ffffffff810646e0)
Location: arch/x86/include/asm/desc.h:119
Inline: False
```
**Symbols:**

```
ffffffff810646e0-ffffffff810646fd: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b644)
Location: arch/x86/include/asm/desc.h:119
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064330)
Location: arch/x86/include/asm/desc.h:119
Inline: False
```
**Symbols:**

```
ffffffff81064330-ffffffff8106434d: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101be64)
Location: arch/x86/include/asm/desc.h:119
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_write_idt_entry
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067800)
Location: arch/x86/include/asm/desc.h:119
Inline: False
```
**Symbols:**

```
ffffffff81067800-ffffffff8106781d: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:152
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066d90)
Location: arch/x86/include/asm/desc.h:152
Inline: False
```
**Symbols:**

```
ffffffff81066d90-ffffffff81066dc2: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106aec0)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff8106aec0-ffffffff8106aef2: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106db80)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff8106db80-ffffffff8106db98: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073bd0)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff81073bd0-ffffffff81073be8: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810776b0)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff810776b0-ffffffff810776c8: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078720)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff81078720-ffffffff81078738: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:136
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fbb0)
Location: arch/x86/include/asm/desc.h:136
Inline: False
```
**Symbols:**

```
ffffffff8107fbb0-ffffffff8107fbc8: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/desc.h:136
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:136
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f7d0)
Location: arch/x86/include/asm/desc.h:136
Inline: False
```
**Symbols:**

```
ffffffff8107f7d0-ffffffff8107f7e8: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/desc.h:136
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:136
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080a20)
Location: arch/x86/include/asm/desc.h:136
Inline: False
```
**Symbols:**

```
ffffffff81080a20-ffffffff81080a38: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f970)
Location: arch/x86/include/asm/desc.h:137
Inline: False
```
**Symbols:**

```
ffffffff8108f970-ffffffff8108f988: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000af3)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030ae9)
Location: arch/x86/include/asm/desc.h:137
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
```
In arch/x86/kernel/paravirt.c (ffffffff81e4e942)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
**Symbols:**

```
ffffffff81e4e942-ffffffff81e4e952: native_write_idt_entry.part.0 (STB_LOCAL)
ffffffff810a0800-ffffffff810a0825: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000b43)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810373b0)
Location: arch/x86/include/asm/desc.h:137
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8540)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
**Symbols:**

```
ffffffff810373b0-ffffffff810373d5: native_write_idt_entry (STB_LOCAL)
ffffffff810b8540-ffffffff810b8565: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81037300)
Location: arch/x86/include/asm/desc.h:137
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
```
In arch/x86/kernel/head64.c (ffffffff81049fb0)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb5c0)
Location: arch/x86/include/asm/desc.h:137
Inline: False
```
**Symbols:**

```
ffffffff81049fb0-ffffffff81049fd0: native_write_idt_entry.constprop.0 (STB_LOCAL)
ffffffff81037300-ffffffff81037325: native_write_idt_entry (STB_LOCAL)
ffffffff810bb5c0-ffffffff810bb5e5: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d590)
Location: arch/x86/include/asm/desc.h:137
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
```
In arch/x86/kernel/head64.c (ffffffff81051210)
Location: arch/x86/include/asm/desc.h:137
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c29d0)
Location: arch/x86/include/asm/desc.h:137
Inline: False
```
**Symbols:**

```
ffffffff81051210-ffffffff81051230: native_write_idt_entry.constprop.0 (STB_LOCAL)
ffffffff8103d590-ffffffff8103d5b5: native_write_idt_entry (STB_LOCAL)
ffffffff810c29d0-ffffffff810c29f5: native_write_idt_entry (STB_LOCAL)
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
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077720)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff81077720-ffffffff81077738: native_write_idt_entry (STB_LOCAL)
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
In arch/x86/kernel/idt.c (ffffffff81022426)
Location: arch/x86/include/asm/desc.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810776d0)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff810776d0-ffffffff810776e8: native_write_idt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_write_idt_entry(gate_desc *idt, int entry, const gate_desc *gate);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/desc.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079770)
Location: arch/x86/include/asm/desc.h:141
Inline: False
```
**Symbols:**

```
ffffffff81079770-ffffffff81079788: native_write_idt_entry (STB_LOCAL)
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
