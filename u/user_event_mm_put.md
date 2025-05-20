# Function: <code>user_event_mm_put</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_user.c (ffffffff812c6cdc)
Location: kernel/trace/trace_events_user.c:722
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:delayed_user_event_mm_put
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
Direct callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:delayed_user_event_mm_put
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
```
**Symbols:**

```
ffffffff812c5680-ffffffff812c56d7: user_event_mm_put.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_user.c (ffffffff812e37a9)
Location: kernel/trace/trace_events_user.c:753
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:delayed_user_event_mm_put
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
Direct callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:delayed_user_event_mm_put
  - kernel/trace/trace_events_user.c:user_event_enabler_write
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
```
**Symbols:**

```
ffffffff812e1eb0-ffffffff812e1f07: user_event_mm_put.part.0 (STB_LOCAL)
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
