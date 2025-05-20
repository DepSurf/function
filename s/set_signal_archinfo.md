# Function: <code>set_signal_archinfo</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107bd10)
Location: arch/x86/mm/fault.c:722
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f745)
Location: arch/x86/mm/fault.c:684
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810807d5)
Location: arch/x86/mm/fault.c:706
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_signal_archinfo(long unsigned int address, long unsigned int error_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81086690)
Location: arch/x86/mm/fault.c:670
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81086690-ffffffff810866f6: set_signal_archinfo (STB_LOCAL)
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
In arch/x86/mm/fault.c (ffffffff81087f6a)
Location: arch/x86/mm/fault.c:629
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff81089052)
Location: arch/x86/mm/fault.c:620
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
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
In arch/x86/mm/fault.c (ffffffff8109849a)
Location: arch/x86/mm/fault.c:621
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
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
In arch/x86/mm/fault.c (ffffffff810ab0f3)
Location: arch/x86/mm/fault.c:621
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
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
In arch/x86/mm/fault.c (ffffffff810c4df5)
Location: arch/x86/mm/fault.c:642
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
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
In arch/x86/mm/fault.c (ffffffff810c8533)
Location: arch/x86/mm/fault.c:622
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
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
In arch/x86/mm/fault.c (ffffffff810d09e4)
Location: arch/x86/mm/fault.c:622
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f7d5)
Location: arch/x86/mm/fault.c:706
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
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
In arch/x86/mm/fault.c (ffffffff8106e845)
Location: arch/x86/mm/fault.c:706
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f785)
Location: arch/x86/mm/fault.c:706
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081875)
Location: arch/x86/mm/fault.c:706
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
