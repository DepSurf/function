# Function: <code>trace_probe_is_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:288
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f597)
Location: kernel/trace/trace_probe.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:298
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117cc77)
Location: kernel/trace/trace_probe.h:298
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:307
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188887)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:307
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b4d7)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_probe.h:306
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198f97)
Location: kernel/trace/trace_probe.h:306
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a8bf0)
Location: kernel/trace/trace_probe.h:318
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811af42c)
Location: kernel/trace/trace_probe.h:318
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
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
In kernel/trace/trace_kprobe.c (ffffffff811b6fb0)
Location: kernel/trace/trace_probe.h:236
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd987)
Location: kernel/trace/trace_probe.h:236
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811c6030)
Location: kernel/trace/trace_probe.h:258
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc827)
Location: kernel/trace/trace_probe.h:258
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811d1d9e)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8c22)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ee78f)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4b12)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ec9df)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f34a2)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ed73f)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f43d2)
Location: kernel/trace/trace_probe.h:272
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff8120a3f8)
Location: kernel/trace/trace_probe.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121e7af)
Location: kernel/trace/trace_probe.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227f72)
Location: kernel/trace/trace_probe.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812463a9)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125de0f)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812680dc)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812933a9)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ae8cf)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ba28c)
Location: kernel/trace/trace_probe.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812b057f)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812d0de7)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dd0dd)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
```
```
In kernel/trace/trace_fprobe.c (ffffffff812df38a)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
  - kernel/trace/trace_fprobe.c:trace_fprobe_is_busy
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
In kernel/trace/trace_eprobe.c (ffffffff812ccb3f)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_is_busy
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ee8e7)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:kprobe_register
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fb1bd)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fd2ea)
Location: kernel/trace/trace_probe.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
  - kernel/trace/trace_fprobe.c:trace_fprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffff800010251f64)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffff800010258a7c)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (c0484e58)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (c048bcac)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (c0000000002f0444)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbeac)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811ca3be)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d1242)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811bd18e)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c4012)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811c818e)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf012)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
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
In kernel/trace/trace_kprobe.c (ffffffff811d63ee)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_is_busy
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd2a2)
Location: kernel/trace/trace_probe.h:273
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_is_busy
```
</details>
</li>
</ul>

## Differences
