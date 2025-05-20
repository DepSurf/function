# Function: <code>native_tss_invalidate_io_bitmap</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810243dc)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff81040496)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fb80)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff8107fb80-ffffffff8107fb8b: native_tss_invalidate_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81024b5c)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff810403e6)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f7a0)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff8107f7a0-ffffffff8107f7ab: native_tss_invalidate_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81026d1c)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff81041db0)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff810808a0)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff810808a0-ffffffff810808ab: native_tss_invalidate_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102b23c)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff81048080)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f7f0)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff8108f7f0-ffffffff8108f7fb: native_tss_invalidate_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102fa2d)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff81051392)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0510)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff810a0510-ffffffff810a051f: native_tss_invalidate_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81036dbd)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff8105e988)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8110)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff810b8110-ffffffff810b811f: native_tss_invalidate_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81036d0d)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff81060078)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb2c0)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff810bb2c0-ffffffff810bb2cf: native_tss_invalidate_io_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_tss_invalidate_io_bitmap();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8103cf0d)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In arch/x86/kernel/process.c (ffffffff8106713d)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c26d0)
Location: arch/x86/include/asm/io_bitmap.h:22
Inline: False
```
**Symbols:**

```
ffffffff810c26d0-ffffffff810c26df: native_tss_invalidate_io_bitmap (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
