# Function: <code>trace_xen_cpu_write_gdt_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bfc0)
Location: include/trace/events/xen.h:480
Inline: True
```
**Symbols:**

```
ffffffff8101bfc0-ffffffff8101c033: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b3f0)
Location: include/trace/events/xen.h:480
Inline: True
```
**Symbols:**

```
ffffffff8101b3f0-ffffffff8101b45c: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bc20)
Location: include/trace/events/xen.h:480
Inline: True
```
**Symbols:**

```
ffffffff8101bc20-ffffffff8101bc8c: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101ecb0)
Location: include/trace/events/xen.h:489
Inline: True
```
**Symbols:**

```
ffffffff8101ecb0-ffffffff8101ed1c: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f750)
Location: include/trace/events/xen.h:455
Inline: True
```
**Symbols:**

```
ffffffff8101f750-ffffffff8101f7c7: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff826d5171)
Location: include/trace/events/xen.h:439
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fc70)
Location: include/trace/events/xen.h:439
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff8101fc70-ffffffff8101fce7: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810219c0)
Location: include/trace/events/xen.h:439
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff810219c0-ffffffff81021a2e: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022300)
Location: include/trace/events/xen.h:443
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff81022300-ffffffff8102236e: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
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
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbb2a)
Location: include/trace/events/xen.h:443
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb79af)
Location: include/trace/events/xen.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810277a8)
Location: include/trace/events/xen.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff810276b0-ffffffff810276f4: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102bd88)
Location: include/trace/events/xen.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff8102bc90-ffffffff8102bcd1: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff83451d30)
Location: include/trace/events/xen.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e9fc)
Location: include/trace/events/xen.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
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
In arch/x86/xen/enlighten_pv.c (ffffffff8368f37c)
Location: include/trace/events/xen.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
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
In arch/x86/xen/enlighten_pv.c (ffffffff838bedec)
Location: include/trace/events/xen.h:423
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
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
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022460)
Location: include/trace/events/xen.h:443
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff81022460-ffffffff810224ce: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
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
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810222c0)
Location: include/trace/events/xen.h:443
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff810222c0-ffffffff8102232e: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_xen_cpu_write_gdt_entry(struct desc_struct *dt, int entrynum, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022570)
Location: include/trace/events/xen.h:443
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
```
**Symbols:**

```
ffffffff81022570-ffffffff810225f5: trace_xen_cpu_write_gdt_entry (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
