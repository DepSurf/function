# Function: <code>get_cpu_gdt_ro</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff8103d951)
Location: arch/x86/include/asm/desc.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066f63)
Location: arch/x86/include/asm/desc.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/cpu/common.c (ffffffff81040548)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b093)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/cpu/common.c (ffffffff81041db0)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106dd23)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/cpu/common.c (ffffffff810433d0)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073d93)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/cpu/common.c (ffffffff810458d0)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077925)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/cpu/common.c (ffffffff81046020)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078995)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a0a0)
Location: arch/x86/include/asm/desc.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fdd5)
Location: arch/x86/include/asm/desc.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049540)
Location: arch/x86/include/asm/desc.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f9f5)
Location: arch/x86/include/asm/desc.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104ad70)
Location: arch/x86/include/asm/desc.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080b15)
Location: arch/x86/include/asm/desc.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051e00)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fa65)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d5fb)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0771)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106bb0a)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8401)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d4ba)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb531)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81076413)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2941)
Location: arch/x86/include/asm/desc.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/cpu/common.c (ffffffff810461a0)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077995)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/ioport.c (ffffffff81024ec2)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/process.c (ffffffff8102d313)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036818)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff818638a1)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/cpu/common.c (ffffffff81045fe0)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077945)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
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
In arch/x86/kernel/cpu/common.c (ffffffff810473e0)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff810799e5)
Location: arch/x86/include/asm/desc.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
</details>
</li>
</ul>

## Differences
