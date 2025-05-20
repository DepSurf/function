# Function: <code>dbc_tty_init</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dbc_tty_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:519
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
```
**Symbols:**

```
ffffffff81926da0-ffffffff81926e6d: dbc_tty_init (STB_LOCAL)
ffffffff81c228a5-ffffffff81c228c2: dbc_tty_init.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190aeba)
Location: drivers/usb/host/xhci-dbgtty.c:519
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab7ca)
Location: drivers/usb/host/xhci-dbgtty.c:517
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dbc_tty_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:537
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81eedbdc-ffffffff81eedc05: dbc_tty_init.cold (STB_LOCAL)
ffffffff81b09c40-ffffffff81b09d4b: dbc_tty_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dbc_tty_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c99a40)
Location: drivers/usb/host/xhci-dbgtty.c:537
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81c99a40-ffffffff81c99b7d: dbc_tty_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dbc_tty_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00df0)
Location: drivers/usb/host/xhci-dbgtty.c:537
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81d00df0-ffffffff81d00f2d: dbc_tty_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dbc_tty_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db6920)
Location: drivers/usb/host/xhci-dbgtty.c:536
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81db6920-ffffffff81db6a5d: dbc_tty_init (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
