# Function: <code>mul_u64_u32_div</code>

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
In kernel/time/timekeeping.c (ffffffff810f4501)
Location: include/linux/math64.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff810fb70d)
Location: include/linux/math64.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff810fe50d)
Location: include/linux/math64.h:218
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff81100876)
Location: include/linux/math64.h:228
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b65c)
Location: include/linux/math64.h:256
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff811174f2)
Location: include/linux/math64.h:256
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122b3d)
Location: include/linux/math64.h:256
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff8112d18a)
Location: include/linux/math64.h:256
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff81139156)
Location: arch/x86/include/asm/div64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff81149515)
Location: arch/x86/include/asm/div64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8100bd20)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/time/timekeeping.c (ffffffff81145985)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8100c6b0)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/time/timekeeping.c (ffffffff811468bb)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8100df81)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/time/timekeeping.c (ffffffff81169f7c)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8100f3cb)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/time/timekeeping.c (ffffffff8119db93)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff81012d7b)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/time/timekeeping.c (ffffffff811dc823)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff8101234b)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/time/timekeeping.c (ffffffff811f0c33)
Location: arch/x86/include/asm/div64.h:93
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In arch/x86/events/intel/core.c (ffffffff81017c6b)
Location: arch/x86/include/asm/div64.h:99
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In kernel/time/timekeeping.c (ffffffff81206d73)
Location: arch/x86/include/asm/div64.h:99
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a37e0)
Location: include/linux/math64.h:256
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 mul_u64_u32_div(u64 a, u32 mul, u32 divisor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ef5b4)
Location: include/linux/math64.h:256
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
**Symbols:**

```
c03ef5b4-c03ef63c: mul_u64_u32_div (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000205438)
Location: include/linux/math64.h:256
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00013036e)
Location: include/linux/math64.h:256
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
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
In kernel/time/timekeeping.c (ffffffff81131906)
Location: arch/x86/include/asm/div64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff81124366)
Location: arch/x86/include/asm/div64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff8112f626)
Location: arch/x86/include/asm/div64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
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
In kernel/time/timekeeping.c (ffffffff8113c046)
Location: arch/x86/include/asm/div64.h:77
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:get_device_system_crosststamp
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
