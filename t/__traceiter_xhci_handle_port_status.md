# Function: <code>__traceiter_xhci_handle_port_status</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_xhci_handle_port_status(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81921f30)
Location: drivers/usb/host/xhci-trace.h:537
Inline: False
```
**Symbols:**

```
ffffffff81921f30-ffffffff81921f77: __traceiter_xhci_handle_port_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_xhci_handle_port_status(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81905630)
Location: drivers/usb/host/xhci-trace.h:537
Inline: False
```
**Symbols:**

```
ffffffff81905630-ffffffff81905675: __traceiter_xhci_handle_port_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_xhci_handle_port_status(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff819a5e30)
Location: drivers/usb/host/xhci-trace.h:540
Inline: False
```
**Symbols:**

```
ffffffff819a5e30-ffffffff819a5e75: __traceiter_xhci_handle_port_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_xhci_handle_port_status(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81b03a80)
Location: drivers/usb/host/xhci-trace.h:540
Inline: False
```
**Symbols:**

```
ffffffff81b03a80-ffffffff81b03acf: __traceiter_xhci_handle_port_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_xhci_handle_port_status(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81c92e10)
Location: drivers/usb/host/xhci-trace.h:540
Inline: False
```
**Symbols:**

```
ffffffff81c92e10-ffffffff81c92e5f: __traceiter_xhci_handle_port_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_xhci_handle_port_status(void *__data, u32 portnum, u32 portsc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81cf9560)
Location: drivers/usb/host/xhci-trace.h:528
Inline: False
```
**Symbols:**

```
ffffffff81cf9560-ffffffff81cf95af: __traceiter_xhci_handle_port_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_xhci_handle_port_status(void *__data, struct xhci_port *port, u32 portsc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-trace.c (ffffffff81daee90)
Location: drivers/usb/host/xhci-trace.h:531
Inline: False
```
**Symbols:**

```
ffffffff81daee90-ffffffff81daeedf: __traceiter_xhci_handle_port_status (STB_GLOBAL)
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
