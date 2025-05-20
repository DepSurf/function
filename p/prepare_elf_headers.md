# Function: <code>prepare_elf_headers</code>

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
In arch/x86/kernel/crash.c (ffffffff8105dc4a)
Location: arch/x86/kernel/crash.c:496
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff8105db52)
Location: arch/x86/kernel/crash.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81060bd7)
Location: arch/x86/kernel/crash.c:488
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff8105fbbf)
Location: arch/x86/kernel/crash.c:489
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81063c0f)
Location: arch/x86/kernel/crash.c:489
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff810668e1)
Location: arch/x86/kernel/crash.c:252
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff8106c901)
Location: arch/x86/kernel/crash.c:253
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81070936)
Location: arch/x86/kernel/crash.c:247
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81071936)
Location: arch/x86/kernel/crash.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81078220)
Location: arch/x86/kernel/crash.c:261
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81078220-ffffffff81078372: prepare_elf_headers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81078220)
Location: arch/x86/kernel/crash.c:261
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81078220-ffffffff81078372: prepare_elf_headers.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/crash.c (ffffffff8107985c)
Location: arch/x86/kernel/crash.c:261
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff810878bc)
Location: arch/x86/kernel/crash.c:248
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81097a5c)
Location: arch/x86/kernel/crash.c:248
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff810ade5c)
Location: arch/x86/kernel/crash.c:233
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff810b0e5c)
Location: arch/x86/kernel/crash.c:233
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prepare_elf_headers(void **addr, long unsigned int *sz, long unsigned int *nr_mem_ranges);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b78d0)
Location: arch/x86/kernel/crash.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:arch_crash_handle_hotplug_event
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810b78d0-ffffffff810b7a3b: prepare_elf_headers (STB_LOCAL)
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
In arch/x86/kernel/crash.c (ffffffff81070936)
Location: arch/x86/kernel/crash.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81060946)
Location: arch/x86/kernel/crash.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81070936)
Location: arch/x86/kernel/crash.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
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
In arch/x86/kernel/crash.c (ffffffff81072946)
Location: arch/x86/kernel/crash.c:245
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
