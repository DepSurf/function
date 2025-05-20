# Function: <code>trace_probe_set_flag</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c49cb)
Location: kernel/trace/trace_probe.h:246
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
```
```
In kernel/trace/trace_probe.c (ffffffff811cba58)
Location: kernel/trace/trace_probe.h:246
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc4ec)
Location: kernel/trace/trace_probe.h:246
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811cf0e4)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d7aab)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8a8a)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811eb3a1)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f444b)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f585e)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811e94f1)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f2dfb)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f41ee)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811ea381)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f3c7b)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4d9a)
Location: kernel/trace/trace_probe.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_eprobe.c (ffffffff8120a312)
Location: kernel/trace/trace_probe.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121b1c1)
Location: kernel/trace/trace_probe.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81224fcb)
Location: kernel/trace/trace_probe.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff81226faa)
Location: kernel/trace/trace_probe.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_eprobe.c (ffffffff812462a2)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125a411)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81264e9b)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff81266b08)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_eprobe.c (ffffffff8129321d)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff812aa831)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812b6a4b)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8d75)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_eprobe.c (ffffffff812b0458)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ccff2)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812d9f3b)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dc3d6)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/trace/trace_fprobe.c (ffffffff812df92e)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812cca20)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ea9e2)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812f7ecb)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa4b6)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fd88e)
Location: kernel/trace/trace_probe.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
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
In kernel/trace/trace_kprobe.c (ffff80001024f968)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffff800010257e1c)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffff800010259b18)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (c0482998)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c048af54)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (c048bac4)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (c0000000002ed0c0)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c0000000002f9e98)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (c0000000002fd378)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811c7704)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d00cb)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d10aa)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811ba4e4)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811c2e9b)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3e7a)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811c54d4)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cde9b)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cee7a)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811d3734)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811dc0fb)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd10a)
Location: kernel/trace/trace_probe.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
</details>
</li>
</ul>

## Differences
