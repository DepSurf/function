# Function: <code>xdbc_early_setup</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff828eab6f)
Location: drivers/usb/early/xhci-dbc.c:555
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff829055ae)
Location: drivers/usb/early/xhci-dbc.c:553
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8290efe9)
Location: drivers/usb/early/xhci-dbc.c:553
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdbc_early_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22d94)
Location: drivers/usb/early/xhci-dbc.c:552
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff82d22d94-ffffffff82d22e93: xdbc_early_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xdbc_early_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83010b8d)
Location: drivers/usb/early/xhci-dbc.c:547
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff83010b8d-ffffffff83010c93: xdbc_early_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8321bda1)
Location: drivers/usb/early/xhci-dbc.c:547
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff833059d8)
Location: drivers/usb/early/xhci-dbc.c:554
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff834beb1e)
Location: drivers/usb/early/xhci-dbc.c:554
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83efca78)
Location: drivers/usb/early/xhci-dbc.c:554
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83722878)
Location: drivers/usb/early/xhci-dbc.c:553
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff839566a8)
Location: drivers/usb/early/xhci-dbc.c:553
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
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
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8291004b)
Location: drivers/usb/early/xhci-dbc.c:553
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
