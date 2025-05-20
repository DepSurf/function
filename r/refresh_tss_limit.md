# Function: <code>refresh_tss_limit</code>

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
In arch/x86/kernel/ioport.c (ffffffff8102e952)
Location: arch/x86/include/asm/desc.h:334
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81035f90)
Location: arch/x86/include/asm/desc.h:334
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
In arch/x86/kernel/ioport.c (ffffffff8103080e)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff810382f0)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/ioport.c (ffffffff81031a7f)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff81039689)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/ioport.c (ffffffff81032d8f)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103a98a)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/ioport.c (ffffffff81034b9f)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103cf8b)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/ioport.c (ffffffff810353d8)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d74b)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/process.c (ffffffff81040467)
Location: arch/x86/include/asm/desc.h:305
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
In arch/x86/kernel/process.c (ffffffff810403b7)
Location: arch/x86/include/asm/desc.h:305
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
In arch/x86/kernel/process.c (ffffffff81041d8c)
Location: arch/x86/include/asm/desc.h:305
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
In arch/x86/kernel/process.c (ffffffff8104805c)
Location: arch/x86/include/asm/desc.h:326
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
In arch/x86/kernel/process.c (ffffffff810512fc)
Location: arch/x86/include/asm/desc.h:326
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
In arch/x86/kernel/process.c (ffffffff8105e8f5)
Location: arch/x86/include/asm/desc.h:326
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
In arch/x86/kernel/process.c (ffffffff8105ffe5)
Location: arch/x86/include/asm/desc.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff810670d1)
Location: arch/x86/include/asm/desc.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/ioport.c (ffffffff81035538)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d8cb)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/ioport.c (ffffffff81024e78)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8102cfb9)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/ioport.c (ffffffff81035398)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103d70b)
Location: arch/x86/include/asm/desc.h:310
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
In arch/x86/kernel/ioport.c (ffffffff810362fd)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8103e80b)
Location: arch/x86/include/asm/desc.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
</details>
</li>
</ul>

## Differences
