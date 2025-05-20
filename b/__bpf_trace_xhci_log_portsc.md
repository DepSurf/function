# Function: <code>__bpf_trace_xhci_log_portsc</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff817b2810)
Location: drivers/usb/host/xhci-trace.h:501
Inline: False
```
**Symbols:**

```
ffffffff817b2810-ffffffff817b281f: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff817d8e50)
Location: drivers/usb/host/xhci-trace.h:501
Inline: False
```
**Symbols:**

```
ffffffff817d8e50-ffffffff817d8e5f: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff818196b0)
Location: drivers/usb/host/xhci-trace.h:531
Inline: False
```
**Symbols:**

```
ffffffff818196b0-ffffffff818196bf: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff8184aa50)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
ffffffff8184aa50-ffffffff8184aa5f: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff8191d330)
Location: drivers/usb/host/xhci-trace.h:520
Inline: True
```
**Symbols:**

```
ffffffff8191d330-ffffffff8191d33f: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81924990)
Location: drivers/usb/host/xhci-trace.h:520
Inline: True
```
**Symbols:**

```
ffffffff81924990-ffffffff8192499f: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81907ea0)
Location: drivers/usb/host/xhci-trace.h:520
Inline: True
```
**Symbols:**

```
ffffffff81907ea0-ffffffff81907eaf: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff819a7cd0)
Location: drivers/usb/host/xhci-trace.h:522
Inline: True
```
**Symbols:**

```
ffffffff819a7cd0-ffffffff819a7cdf: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81b06710)
Location: drivers/usb/host/xhci-trace.h:522
Inline: True
```
**Symbols:**

```
ffffffff81b06710-ffffffff81b06729: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81c95ba0)
Location: drivers/usb/host/xhci-trace.h:522
Inline: True
```
**Symbols:**

```
ffffffff81c95ba0-ffffffff81c95bb9: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81cfc300)
Location: drivers/usb/host/xhci-trace.h:511
Inline: True
```
**Symbols:**

```
ffffffff81cfc300-ffffffff81cfc319: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, struct xhci_port *port, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81db1c80)
Location: drivers/usb/host/xhci-trace.h:511
Inline: False
```
**Symbols:**

```
ffffffff81db1c80-ffffffff81db1c97: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffff800010a890e0)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
ffff800010a890e0-ffff800010a890fc: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (c0b5ca1c)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
c0b5ca1c-c0b5ca44: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (c000000000b650a0)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
c000000000b650a0-c000000000b650cc: __bpf_trace_xhci_log_portsc (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81802e00)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
ffffffff81802e00-ffffffff81802e0f: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff817c7fa0)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
ffffffff817c7fa0-ffffffff817c7faf: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff8183f8d0)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
ffffffff8183f8d0-ffffffff8183f8df: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_xhci_log_portsc(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81859da0)
Location: drivers/usb/host/xhci-trace.h:520
Inline: False
```
**Symbols:**

```
ffffffff81859da0-ffffffff81859daf: __bpf_trace_xhci_log_portsc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_port *port</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 portnum</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
