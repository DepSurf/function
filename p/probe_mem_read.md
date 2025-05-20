# Function: <code>probe_mem_read</code>

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
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b5c4e)
Location: kernel/trace/trace_kprobe.c:900
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bc22f)
Location: kernel/trace/trace_uprobe.c:137
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c4a93)
Location: kernel/trace/trace_kprobe.c:927
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd50e)
Location: kernel/trace/trace_uprobe.c:137
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811d0733)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d9b2c)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811ec1dc)
Location: kernel/trace/trace_kprobe.c:1297
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f65dc)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811ea32c)
Location: kernel/trace/trace_kprobe.c:1317
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4fb2)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811eb79c)
Location: kernel/trace/trace_kprobe.c:1322
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5ea2)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff812099cb)
Location: kernel/trace/trace_eprobe.c:468
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c6ae)
Location: kernel/trace/trace_kprobe.c:1316
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff81226069)
Location: kernel/trace/trace_uprobe.c:127
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff8124585d)
Location: kernel/trace/trace_eprobe.c:545
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125b482)
Location: kernel/trace/trace_kprobe.c:1312
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff81265cf6)
Location: kernel/trace/trace_uprobe.c:128
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff81294eec)
Location: kernel/trace/trace_eprobe.c:500
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ad04a)
Location: kernel/trace/trace_kprobe.c:1266
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b7661)
Location: kernel/trace/trace_uprobe.c:129
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_eprobe.c (ffffffff812b160a)
Location: kernel/trace/trace_probe_kernel.h:110
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cef00)
Location: kernel/trace/trace_probe_kernel.h:110
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812daf10)
Location: kernel/trace/trace_uprobe.c:129
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e121f)
Location: kernel/trace/trace_probe_kernel.h:110
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
In kernel/trace/trace_eprobe.c (ffffffff812cdbba)
Location: kernel/trace/trace_probe_kernel.h:110
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec900)
Location: kernel/trace/trace_probe_kernel.h:110
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9169)
Location: kernel/trace/trace_uprobe.c:124
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff26f)
Location: kernel/trace/trace_probe_kernel.h:110
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
In kernel/trace/trace_kprobe.c (ffff80001024efa8)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a024)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (c04820c8)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c048d518)
Location: kernel/trace/trace_uprobe.c:131
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
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002eb8f4)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c0000000002fda04)
Location: kernel/trace/trace_uprobe.c:131
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c8d53)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d214c)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811bbb33)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c4f1c)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811c6b23)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cff1c)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
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
In kernel/trace/trace_kprobe.c (ffffffff811d4d83)
Location: kernel/trace/trace_kprobe.c:1111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (ffffffff811de1bc)
Location: kernel/trace/trace_uprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
</details>
</li>
</ul>

## Differences
