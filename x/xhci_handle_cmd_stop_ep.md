# Function: <code>xhci_handle_cmd_stop_ep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8165a5c5)
Location: drivers/usb/host/xhci-ring.c:636
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816badad)
Location: drivers/usb/host/xhci-ring.c:643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e8fa5)
Location: drivers/usb/host/xhci-ring.c:698
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fd393)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81769f1a)
Location: drivers/usb/host/xhci-ring.c:688
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff817ab0ca)
Location: drivers/usb/host/xhci-ring.c:688
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff817d11f7)
Location: drivers/usb/host/xhci-ring.c:688
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81810960-ffffffff81810d55: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff818135d4-ffffffff8181360d: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81841b50-ffffffff81841f45: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff818447d6-ffffffff8184480f: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:721
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81915d60-ffffffff81916154: xhci_handle_cmd_stop_ep.constprop.0.isra.0 (STB_LOCAL)
ffffffff81917523-ffffffff8191755c: xhci_handle_cmd_stop_ep.constprop.0.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:726
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8191d350-ffffffff8191d724: xhci_handle_cmd_stop_ep.constprop.0.isra.0 (STB_LOCAL)
ffffffff81c22436-ffffffff81c2246f: xhci_handle_cmd_stop_ep.constprop.0.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1010
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff818ffb40-ffffffff818ffe17: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff81c145cd-ffffffff81c145e6: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1067
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8199f290-ffffffff8199f5c9: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff81d21742-ffffffff81d2175d: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1059
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81afc830-ffffffff81afcb71: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff81eed373-ffffffff81eed38e: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81c8b380)
Location: drivers/usb/host/xhci-ring.c:1059
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81c8b380-ffffffff81c8b6b3: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81cf1ed0)
Location: drivers/usb/host/xhci-ring.c:1090
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81cf1ed0-ffffffff81cf2203: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da7840)
Location: drivers/usb/host/xhci-ring.c:1098
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81da7840-ffffffff81da7b73: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a80a30)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffff800010a80a30-ffff800010a80ea0: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c0b53d34)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c0b53d34-c0b541dc: xhci_handle_cmd_stop_ep.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c000000000b59980)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c000000000b59980-c000000000b59f3c: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffe0006972a4)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffe0006972a4-ffffffe000697664: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817f9f00-ffffffff817fa2f5: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff817fcb86-ffffffff817fcbbf: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817bf0a0-ffffffff817bf495: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff817c1d26-ffffffff817c1d5f: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff818369d0-ffffffff81836dc5: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff81839656-ffffffff8183968f: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:699
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81850d50-ffffffff8185115e: xhci_handle_cmd_stop_ep.isra.0 (STB_LOCAL)
ffffffff81853aa9-ffffffff81853ae2: xhci_handle_cmd_stop_ep.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
