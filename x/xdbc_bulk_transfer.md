# Function: <code>xdbc_bulk_transfer</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int xdbc_bulk_transfer(void *data, int size, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff817df540)
Location: drivers/usb/early/xhci-dbc.c:463
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff817df540-ffffffff817df78b: xdbc_bulk_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xdbc_bulk_transfer(void *data, int size, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8181ffd0)
Location: drivers/usb/early/xhci-dbc.c:463
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8181ffd0-ffffffff81820220: xdbc_bulk_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xdbc_bulk_transfer(void *data, int size, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81851440)
Location: drivers/usb/early/xhci-dbc.c:463
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81851440-ffffffff81851690: xdbc_bulk_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81923110)
Location: drivers/usb/early/xhci-dbc.c:462
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
```
**Symbols:**

```
ffffffff81923110-ffffffff81923335: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8192a840)
Location: drivers/usb/early/xhci-dbc.c:457
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
```
**Symbols:**

```
ffffffff8192a840-ffffffff8192aa65: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8190dd60)
Location: drivers/usb/early/xhci-dbc.c:457
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8190dd60-ffffffff8190df9c: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff819aeb80)
Location: drivers/usb/early/xhci-dbc.c:464
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff819aeb80-ffffffff819aedbc: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0d630)
Location: drivers/usb/early/xhci-dbc.c:464
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81b0d630-ffffffff81b0d871: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9d6d0)
Location: drivers/usb/early/xhci-dbc.c:464
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81c9d6d0-ffffffff81c9d911: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81d04ae0)
Location: drivers/usb/early/xhci-dbc.c:464
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81d04ae0-ffffffff81d04c8c: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
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
In drivers/usb/early/xhci-dbc.c (ffffffff81dba6a0)
Location: drivers/usb/early/xhci-dbc.c:464
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81dba6a0-ffffffff81dba84c: xdbc_bulk_transfer.isra.0 (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xdbc_bulk_transfer(void *data, int size, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81860840)
Location: drivers/usb/early/xhci-dbc.c:463
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81860840-ffffffff81860a90: xdbc_bulk_transfer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
