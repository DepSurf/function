# Function: <code>usb_calc_bus_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160c480)
Location: drivers/usb/core/hcd.c:1195
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff8160c480-ffffffff8160c656: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166c040)
Location: drivers/usb/core/hcd.c:1187
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff8166c040-ffffffff8166c209: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81699d40)
Location: drivers/usb/core/hcd.c:1188
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff81699d40-ffffffff81699f09: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816af030)
Location: drivers/usb/core/hcd.c:1191
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff816af030-ffffffff816af1ad: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171a650)
Location: drivers/usb/core/hcd.c:1180
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff8171a650-ffffffff8171a7ce: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81759380)
Location: drivers/usb/core/hcd.c:1182
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff81759380-ffffffff817594fa: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177d8f0)
Location: drivers/usb/core/hcd.c:1180
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff8177d8f0-ffffffff8177da6a: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bbca0)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff817bbca0-ffffffff817bbe27: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ec4d0)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff817ec4d0-ffffffff817ec657: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bbb30)
Location: drivers/usb/core/hcd.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818bbb30-ffffffff818bbcb9: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c88f0)
Location: drivers/usb/core/hcd.c:1087
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818c88f0-ffffffff818c8a79: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818abf30)
Location: drivers/usb/core/hcd.c:1087
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818abf30-ffffffff818ac0b9: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81940f80)
Location: drivers/usb/core/hcd.c:1094
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81940f80-ffffffff81941109: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a993b0)
Location: drivers/usb/core/hcd.c:1094
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81a993b0-ffffffff81a99599: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1d390)
Location: drivers/usb/core/hcd.c:1094
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c1d390-ffffffff81c1d56d: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c84280)
Location: drivers/usb/core/hcd.c:1098
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c84280-ffffffff81c8445a: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d38c80)
Location: drivers/usb/core/hcd.c:1073
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81d38c80-ffffffff81d38e5a: usb_calc_bus_time (STB_GLOBAL)
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1b5b0)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffff800010a1b5b0-ffff800010a1b7f0: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af3588)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
c0af3588-c0af3738: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad4c70)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
c000000000ad4c70-c000000000ad4eb4: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe00063fb8a)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffe00063fb8a-ffffffe00063fd02: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a48b0)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff817a48b0-ffffffff817a4a37: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817963f0)
Location: drivers/usb/core/hcd.c:1085
Inline: False
```
**Symbols:**

```
ffffffff817963f0-ffffffff81796577: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e1350)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff817e1350-ffffffff817e14d7: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fb740)
Location: drivers/usb/core/hcd.c:1085
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
**Symbols:**

```
ffffffff817fb740-ffffffff817fb8c7: usb_calc_bus_time (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
