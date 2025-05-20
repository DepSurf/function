# Function: <code>__flush_tlb_local</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a99e)
Location: arch/x86/include/asm/paravirt.h:56
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
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
In arch/x86/mm/tlb.c (ffffffff8108ac0e)
Location: arch/x86/include/asm/paravirt.h:56
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
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
In arch/x86/mm/tlb.c (ffffffff8108b72e)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
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
In arch/x86/mm/tlb.c (ffffffff8109ad0e)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
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
In arch/x86/mm/tlb.c (ffffffff810ae0b7)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
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
In arch/x86/mm/tlb.c (ffffffff810c8357)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
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
In arch/x86/mm/tlb.c (ffffffff810cba90)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
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
In arch/x86/mm/tlb.c (ffffffff810d4120)
Location: arch/x86/include/asm/paravirt.h:73
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_func
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
