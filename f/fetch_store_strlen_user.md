# Function: <code>fetch_store_strlen_user</code>

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
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c4b03)
Location: kernel/trace/trace_kprobe.c:868
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd596)
Location: kernel/trace/trace_uprobe.c:208
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d07a3)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d9bd6)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ec31d)
Location: kernel/trace/trace_kprobe.c:1205
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6681)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ea46d)
Location: kernel/trace/trace_kprobe.c:1225
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f504f)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb8d4)
Location: kernel/trace/trace_kprobe.c:1230
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5f39)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81209a51)
Location: kernel/trace/trace_eprobe.c:376
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c734)
Location: kernel/trace/trace_kprobe.c:1224
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff81226100)
Location: kernel/trace/trace_uprobe.c:198
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812459ab)
Location: kernel/trace/trace_eprobe.c:453
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125b5cf)
Location: kernel/trace/trace_kprobe.c:1220
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff81265d8f)
Location: kernel/trace/trace_uprobe.c:199
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812953a2)
Location: kernel/trace/trace_eprobe.c:459
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ad4e4)
Location: kernel/trace/trace_kprobe.c:1225
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7ced)
Location: kernel/trace/trace_uprobe.c:200
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812b1a9e)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b5453)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cf2fd)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db3e4)
Location: kernel/trace/trace_uprobe.c:201
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e1663)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812ce04e)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d1ac3)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/trace_kprobe.c (ffffffff812eccfd)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f94bd)
Location: kernel/trace/trace_uprobe.c:196
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff6b3)
Location: kernel/trace/trace_probe_kernel.h:13
Inline: True
Inline callers:
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
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff80001024f024)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a0c8)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0482014)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c048d2f4)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002eb8c8)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c0000000002fdabc)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c8dc3)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d21f6)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811bbba3)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c4fc6)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c6b93)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cffc6)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d4df3)
Location: kernel/trace/trace_kprobe.c:1052
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811de266)
Location: kernel/trace/trace_uprobe.c:202
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
</ul>

## Differences
