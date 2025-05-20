# Function: <code>trace_seq_acquire</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
char *trace_seq_acquire(struct trace_seq *s, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8128cbc0)
Location: kernel/trace/trace_seq.c:420
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
**Symbols:**

```
ffffffff8128cbc0-ffffffff8128cc45: trace_seq_acquire (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *trace_seq_acquire(struct trace_seq *s, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff812a7f90)
Location: kernel/trace/trace_seq.c:421
Inline: False
Direct callers:
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_doorbell
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb
```
**Symbols:**

```
ffffffff812a7f90-ffffffff812a8015: trace_seq_acquire (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
