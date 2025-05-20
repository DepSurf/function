# Function: <code>microcode_fini_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void microcode_fini_cpu(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c782)
Location: arch/x86/kernel/cpu/microcode/core.c:462
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d3a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1026
Inline: False
```
**Symbols:**

```
ffffffff8104d3a0-ffffffff8104d3cf: microcode_fini_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void microcode_fini_cpu(int cpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104cdb4)
Location: arch/x86/kernel/cpu/microcode/core.c:454
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d3f0)
Location: arch/x86/kernel/cpu/microcode/intel.c:1084
Inline: False
```
**Symbols:**

```
ffffffff8104d3f0-ffffffff8104d41f: microcode_fini_cpu (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ec47)
Location: arch/x86/kernel/cpu/microcode/core.c:529
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104eb77)
Location: arch/x86/kernel/cpu/microcode/core.c:569
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810524e7)
Location: arch/x86/kernel/cpu/microcode/core.c:677
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055207)
Location: arch/x86/kernel/cpu/microcode/core.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810528a7)
Location: arch/x86/kernel/cpu/microcode/core.c:684
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055ab8)
Location: arch/x86/kernel/cpu/microcode/core.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056388)
Location: arch/x86/kernel/cpu/microcode/core.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b908)
Location: arch/x86/kernel/cpu/microcode/core.c:688
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a358)
Location: arch/x86/kernel/cpu/microcode/core.c:686
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105acf8)
Location: arch/x86/kernel/cpu/microcode/core.c:686
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81064235)
Location: arch/x86/kernel/cpu/microcode/core.c:686
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81070d94)
Location: arch/x86/kernel/cpu/microcode/core.c:585
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81080ce6)
Location: arch/x86/kernel/cpu/microcode/core.c:542
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81083136)
Location: arch/x86/kernel/cpu/microcode/core.c:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8108ab76)
Location: arch/x86/kernel/cpu/microcode/core.c:750
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055f08)
Location: arch/x86/kernel/cpu/microcode/core.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046118)
Location: arch/x86/kernel/cpu/microcode/core.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056338)
Location: arch/x86/kernel/cpu/microcode/core.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810577d8)
Location: arch/x86/kernel/cpu/microcode/core.c:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_device_remove
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
