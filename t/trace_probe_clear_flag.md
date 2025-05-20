# Function: <code>trace_probe_clear_flag</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811c37e7)
Location: kernel/trace/trace_probe.h:252
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cbb2c)
Location: kernel/trace/trace_probe.h:252
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc832)
Location: kernel/trace/trace_probe.h:252
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_kprobe.c (ffffffff811cf1cb)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d7ba1)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8c4c)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811eb47b)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f4541)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4b3e)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811e95cb)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f2ef1)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f34ce)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811ea45b)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f3d71)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f43fe)
Location: kernel/trace/trace_probe.h:266
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_eprobe.c (ffffffff8120a3f1)
Location: kernel/trace/trace_probe.h:268
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c4ce)
Location: kernel/trace/trace_probe.h:268
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812250c1)
Location: kernel/trace/trace_probe.h:268
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227f7c)
Location: kernel/trace/trace_probe.h:268
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_eprobe.c (ffffffff812463a2)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125b104)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81264fa2)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff812680ea)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_eprobe.c (ffffffff812933a2)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ab7d4)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812b6b72)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ba29a)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
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
In kernel/trace/trace_eprobe.c (ffffffff812b0578)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cdd30)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812da062)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dd0eb)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/trace/trace_fprobe.c (ffffffff812df382)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812ccb38)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_kprobe.c (ffffffff812eb730)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812f7ff2)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fb1cb)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fd2e2)
Location: kernel/trace/trace_probe.h:276
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
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
In kernel/trace/trace_kprobe.c (ffff80001024fa54)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffff800010257f28)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffff800010258ab8)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (c0482a94)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c048b048)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (c048bce8)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (c0000000002ed240)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c0000000002fa010)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbf10)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811c77eb)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d01c1)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d126c)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811ba5cb)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811c2f91)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c403c)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811c55bb)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cdf91)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf03c)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811d381b)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811dc1f1)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_remove_file
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd2cc)
Location: kernel/trace/trace_probe.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
</details>
</li>
</ul>

## Differences
