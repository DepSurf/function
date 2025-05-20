# Function: <code>xdbc_start</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff817df790)
Location: drivers/usb/early/xhci-dbc.c:417
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff817df790-ffffffff817df968: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81820220)
Location: drivers/usb/early/xhci-dbc.c:417
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81820220-ffffffff818203f8: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81851690)
Location: drivers/usb/early/xhci-dbc.c:417
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81851690-ffffffff81851868: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81923430)
Location: drivers/usb/early/xhci-dbc.c:416
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
```
**Symbols:**

```
ffffffff81923430-ffffffff819234de: xdbc_start.part.0 (STB_LOCAL)
ffffffff819234e0-ffffffff81923542: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8192aec0)
Location: drivers/usb/early/xhci-dbc.c:411
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
```
**Symbols:**

```
ffffffff8192aec0-ffffffff8192b015: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e300)
Location: drivers/usb/early/xhci-dbc.c:411
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8190e300-ffffffff8190e534: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff819aedc0)
Location: drivers/usb/early/xhci-dbc.c:418
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff819aedc0-ffffffff819aef93: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0d880)
Location: drivers/usb/early/xhci-dbc.c:418
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81b0d880-ffffffff81b0da77: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9d930)
Location: drivers/usb/early/xhci-dbc.c:418
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81c9d930-ffffffff81c9db27: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81d04ca0)
Location: drivers/usb/early/xhci-dbc.c:418
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81d04ca0-ffffffff81d04ea0: xdbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81dba860)
Location: drivers/usb/early/xhci-dbc.c:418
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81dba860-ffffffff81dbaa60: xdbc_start (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xdbc_start();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81860a90)
Location: drivers/usb/early/xhci-dbc.c:417
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff81860a90-ffffffff81860c68: xdbc_start (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
