# Function: <code>xdbc_bios_handoff</code>

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
In drivers/usb/early/xhci-dbc.c (ffffffff828eaab5)
Location: drivers/usb/early/xhci-dbc.c:150
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
In drivers/usb/early/xhci-dbc.c (ffffffff829054f4)
Location: drivers/usb/early/xhci-dbc.c:150
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
In drivers/usb/early/xhci-dbc.c (ffffffff8290ef2f)
Location: drivers/usb/early/xhci-dbc.c:150
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
void xdbc_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22af0)
Location: drivers/usb/early/xhci-dbc.c:149
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff82d22af0-ffffffff82d22bae: xdbc_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdbc_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff830108e9)
Location: drivers/usb/early/xhci-dbc.c:144
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff830108e9-ffffffff830109a7: xdbc_bios_handoff (STB_LOCAL)
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
In drivers/usb/early/xhci-dbc.c (ffffffff8321bcd2)
Location: drivers/usb/early/xhci-dbc.c:144
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
In drivers/usb/early/xhci-dbc.c (ffffffff83305921)
Location: drivers/usb/early/xhci-dbc.c:151
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
In drivers/usb/early/xhci-dbc.c (ffffffff834bea5f)
Location: drivers/usb/early/xhci-dbc.c:151
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
In drivers/usb/early/xhci-dbc.c (ffffffff83efca10)
Location: drivers/usb/early/xhci-dbc.c:151
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
In drivers/usb/early/xhci-dbc.c (ffffffff83722810)
Location: drivers/usb/early/xhci-dbc.c:151
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
In drivers/usb/early/xhci-dbc.c (ffffffff83956640)
Location: drivers/usb/early/xhci-dbc.c:151
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
In drivers/usb/early/xhci-dbc.c (ffffffff8290ff91)
Location: drivers/usb/early/xhci-dbc.c:150
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
