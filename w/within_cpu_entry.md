# Function: <code>within_cpu_entry</code>

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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103df2b)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: True
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103dfaf)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: True
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103f8f6)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: True
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104570f)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: True
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104e29e)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool within_cpu_entry(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b130)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: False
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff8105b130-ffffffff8105b373: within_cpu_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool within_cpu_entry(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105c670)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: False
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff8105c670-ffffffff8105c8b3: within_cpu_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool within_cpu_entry(long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81063730)
Location: arch/x86/kernel/hw_breakpoint.c:263
Inline: False
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff81063730-ffffffff81063973: within_cpu_entry (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
