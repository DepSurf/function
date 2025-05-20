# Function: <code>xhci_dbc_mem_init</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772e61)
Location: drivers/usb/host/xhci-dbgcap.c:372
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3411)
Location: drivers/usb/host/xhci-dbgcap.c:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d99cf)
Location: drivers/usb/host/xhci-dbgcap.c:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a290)
Location: drivers/usb/host/xhci-dbgcap.c:374
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff8181a290-ffffffff8181a6c7: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184b630)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff8184b630-ffffffff8184ba36: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e070)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_start
```
**Symbols:**

```
ffffffff8191e070-ffffffff8191e476: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925650)
Location: drivers/usb/host/xhci-dbgcap.c:467
Inline: True
```
**Symbols:**

```
ffffffff81925650-ffffffff81925a85: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81908d50)
Location: drivers/usb/host/xhci-dbgcap.c:467
Inline: True
```
**Symbols:**

```
ffffffff81908d50-ffffffff81909173: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a95d0)
Location: drivers/usb/host/xhci-dbgcap.c:467
Inline: True
```
**Symbols:**

```
ffffffff819a95d0-ffffffff819a99f3: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b076a0)
Location: drivers/usb/host/xhci-dbgcap.c:467
Inline: True
```
**Symbols:**

```
ffffffff81b076a0-ffffffff81b07ace: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c96f80)
Location: drivers/usb/host/xhci-dbgcap.c:467
Inline: True
```
**Symbols:**

```
ffffffff81c96f80-ffffffff81c973ae: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe290)
Location: drivers/usb/host/xhci-dbgcap.c:467
Inline: True
```
**Symbols:**

```
ffffffff81cfe290-ffffffff81cfe6c1: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db4a40)
Location: drivers/usb/host/xhci-dbgcap.c:481
Inline: True
```
**Symbols:**

```
ffffffff81db4a40-ffffffff81db4f21: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8aa18)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffff800010a8aa18-ffff800010a8adbc: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5d6d8)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
c0b5d6d8-c0b5dad4: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66290)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
c000000000b66290-c000000000b6675c: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069fecc)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffe00069fecc-ffffffe0006a031c: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8b80)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817c8b80-ffffffff817c8f86: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff818404b0)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff818404b0-ffffffff818408b6: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185a980)
Location: drivers/usb/host/xhci-dbgcap.c:373
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff8185a980-ffffffff8185ad86: xhci_dbc_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
