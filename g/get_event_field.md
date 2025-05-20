# Function: <code>get_event_field</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81209130)
Location: kernel/trace/trace_eprobe.c:303
Inline: True
Direct callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
**Symbols:**

```
ffffffff81209130-ffffffff81209178: get_event_field.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81244f70)
Location: kernel/trace/trace_eprobe.c:317
Inline: True
Direct callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
**Symbols:**

```
ffffffff81244f70-ffffffff81245066: get_event_field.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81292e10)
Location: kernel/trace/trace_eprobe.c:323
Inline: True
Direct callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
**Symbols:**

```
ffffffff81292e10-ffffffff81292ee3: get_event_field.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_eprobe.c (ffffffff812b1433)
Location: kernel/trace/trace_eprobe.c:293
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
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
In kernel/trace/trace_eprobe.c (ffffffff812cd9e3)
Location: kernel/trace/trace_eprobe.c:297
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
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
