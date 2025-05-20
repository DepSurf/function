# Function: <code>get_loc_data</code>

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
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.h:90
Inline: True
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
In kernel/trace/trace_probe.c (ffffffff8117a9b5)
Location: kernel/trace/trace_probe.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
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
In kernel/trace/trace_probe.c (ffffffff811865c5)
Location: kernel/trace/trace_probe.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
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
In kernel/trace/trace_probe.c (ffffffff81189225)
Location: kernel/trace/trace_probe.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
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
In kernel/trace/trace_probe.c (ffffffff81196ea5)
Location: kernel/trace/trace_probe.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
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
In kernel/trace/trace_probe.c (ffffffff811ac736)
Location: kernel/trace/trace_probe.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
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
In kernel/trace/trace_kprobe.c (ffffffff811b5d59)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811bac10)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bc143)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811c4b4e)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811c9cb0)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd78d)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811d07ee)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811d59e0)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d9dfb)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811ec473)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811f22d3)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f68a6)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811ea5c3)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811f0ca3)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5199)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811eba1f)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811f1c03)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6083)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff81209ba9)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c951)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff81222da3)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff81226386)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff8124591e)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125b543)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff81262cff)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff81265e20)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff81294d54)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff81297f56)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ace0c)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff812b468f)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7798)
Location: kernel/trace/trace_probe.h:64
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff812b14c1)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b4fc6)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ced46)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff812d6fff)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dadb5)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e1023)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff812cda71)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d162e)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec746)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff812f4b0f)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f900d)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff073)
Location: kernel/trace/trace_probe.h:67
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff80001024f0c4)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffff800010255dc0)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a21c)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0481f8c)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (c0488ed8)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (c048d340)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002eb7b4)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (c0000000002f60a0)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (c0000000002fdbf8)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
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
In kernel/trace/trace_kprobe.c (ffffffff811c8e0e)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811ce000)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d241b)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811bbbee)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811c0dd0)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c51eb)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811c6bde)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811cbdd0)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d01eb)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811d4e3e)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_probe.c (ffffffff811da030)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:print_type_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811de48b)
Location: kernel/trace/trace_probe.h:65
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
</ul>

## Differences
