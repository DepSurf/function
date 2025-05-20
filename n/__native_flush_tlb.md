# Function: <code>__native_flush_tlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064909)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064559)
Location: arch/x86/include/asm/tlbflush.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067a39)
Location: arch/x86/include/asm/tlbflush.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066cb9)
Location: arch/x86/include/asm/tlbflush.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
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
In arch/x86/kernel/paravirt.c (ffffffff8106b336)
Location: arch/x86/include/asm/tlbflush.h:351
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5995)
Location: arch/x86/include/asm/tlbflush.h:351
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff8106e005)
Location: arch/x86/include/asm/tlbflush.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa6b)
Location: arch/x86/include/asm/tlbflush.h:396
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81074045)
Location: arch/x86/include/asm/tlbflush.h:384
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6728)
Location: arch/x86/include/asm/tlbflush.h:384
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81077bc5)
Location: arch/x86/include/asm/tlbflush.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedc4)
Location: arch/x86/include/asm/tlbflush.h:386
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81078c35)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c523d)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c35)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b01d5)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff810677a5)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83c2)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81077be5)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c30d4)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
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
In arch/x86/kernel/paravirt.c (ffffffff81079c85)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c625d)
Location: arch/x86/include/asm/tlbflush.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
</ul>

## Differences
