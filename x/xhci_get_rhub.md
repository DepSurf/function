# Function: <code>xhci_get_rhub</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817b00ca)
Location: drivers/usb/host/xhci-hub.c:544
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff817ae140-ffffffff817ae17a: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817d6a35)
Location: drivers/usb/host/xhci-hub.c:544
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff817d4510-ffffffff817d454a: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81816eb5)
Location: drivers/usb/host/xhci-hub.c:545
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff818140b0-ffffffff818140f1: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff818481e5)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81845270-ffffffff818452b1: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8191a8f5)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81918440-ffffffff81918484: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8192126d)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff8191ed60-ffffffff8191eda4: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8190497d)
Location: drivers/usb/host/xhci-hub.c:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81902480-ffffffff819024c4: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff819a517d)
Location: drivers/usb/host/xhci-hub.c:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff819a1fc0-ffffffff819a2004: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81b02b5d)
Location: drivers/usb/host/xhci-hub.c:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81aff6e0-ffffffff81aff72a: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81c91bfd)
Location: drivers/usb/host/xhci-hub.c:655
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81c8e9b0-ffffffff81c8e9fa: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81cf82ed)
Location: drivers/usb/host/xhci-hub.c:662
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81cf5450-ffffffff81cf549a: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81dadc1d)
Location: drivers/usb/host/xhci-hub.c:662
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81daad40-ffffffff81daad8a: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffff800010a87270)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffff800010a83d58-ffff800010a83da8: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c0b5a1d8)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
c0b572a0-c0b572e4: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c000000000b616b0)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
c000000000b5d890-c000000000b5d8f4: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffe00069cae4)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffe000699d5c-ffffffe000699da6: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81800595)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff817fd620-ffffffff817fd661: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817c5735)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff817c27c0-ffffffff817c2801: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8183d065)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff8183a0f0-ffffffff8183a131: xhci_get_rhub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct xhci_hub *xhci_get_rhub(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81857535)
Location: drivers/usb/host/xhci-hub.c:554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
Direct callers:
  - drivers/usb/host/xhci.c:xhci_find_raw_port_number
```
**Symbols:**

```
ffffffff81854580-ffffffff818545c1: xhci_get_rhub (STB_GLOBAL)
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
