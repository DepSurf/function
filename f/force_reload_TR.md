# Function: <code>force_reload_TR</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8102e962)
Location: arch/x86/include/asm/desc.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81036080)
Location: arch/x86/include/asm/desc.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff8103081e)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103840b)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81031a8f)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81039880)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81032d9f)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103ac52)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81034baf)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d212)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810353e8)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d9d2)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
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
In arch/x86/kernel/process.c (ffffffff810404a2)
Location: arch/x86/include/asm/desc.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff810403f2)
Location: arch/x86/include/asm/desc.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81041dbc)
Location: arch/x86/include/asm/desc.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8104808c)
Location: arch/x86/include/asm/desc.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff810513a1)
Location: arch/x86/include/asm/desc.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff8105e997)
Location: arch/x86/include/asm/desc.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff81060087)
Location: arch/x86/include/asm/desc.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void force_reload_TR();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81066870)
Location: arch/x86/include/asm/desc.h:303
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
**Symbols:**

```
ffffffff81066870-ffffffff81066909: force_reload_TR (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81035548)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103db52)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81024e88)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8102d2d8)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810353a8)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d992)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff81036345)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103eaa9)
Location: arch/x86/include/asm/desc.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
