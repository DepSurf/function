# Function: <code>uncore_mmio_is_valid_offset</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019d38)
Location: arch/x86/events/intel/uncore.h:224
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ec6f)
Location: arch/x86/events/intel/uncore.h:224
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff8101b0b8)
Location: arch/x86/events/intel/uncore.h:237
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810200ff)
Location: arch/x86/events/intel/uncore.h:237
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101d9eb)
Location: arch/x86/events/intel/uncore.h:238
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81c96c7c)
Location: arch/x86/events/intel/uncore.h:238
Inline: True
```
**Symbols:**

```
ffffffff81c96c7c-ffffffff81c96ca8: uncore_mmio_is_valid_offset.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff8102040f)
Location: arch/x86/events/intel/uncore.h:238
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102785b)
Location: arch/x86/events/intel/uncore.h:238
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81024d0f)
Location: arch/x86/events/intel/uncore.h:254
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102d93b)
Location: arch/x86/events/intel/uncore.h:254
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81024c0f)
Location: arch/x86/events/intel/uncore.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102dcbb)
Location: arch/x86/events/intel/uncore.h:257
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff8102ad6f)
Location: arch/x86/events/intel/uncore.h:257
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81033ceb)
Location: arch/x86/events/intel/uncore.h:257
Inline: True
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
