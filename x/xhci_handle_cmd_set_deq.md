# Function: <code>xhci_handle_cmd_set_deq</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff8165a311)
Location: drivers/usb/host/xhci-ring.c:953
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
In drivers/usb/host/xhci-ring.c (ffffffff816bab0d)
Location: drivers/usb/host/xhci-ring.c:969
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
In drivers/usb/host/xhci-ring.c (ffffffff816e8dc2)
Location: drivers/usb/host/xhci-ring.c:1021
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
In drivers/usb/host/xhci-ring.c (ffffffff816fd02e)
Location: drivers/usb/host/xhci-ring.c:1038
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
In drivers/usb/host/xhci-ring.c (ffffffff81769bbc)
Location: drivers/usb/host/xhci-ring.c:1024
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
In drivers/usb/host/xhci-ring.c (ffffffff817aaddc)
Location: drivers/usb/host/xhci-ring.c:1024
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
In drivers/usb/host/xhci-ring.c (ffffffff817d0d6c)
Location: drivers/usb/host/xhci-ring.c:1024
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
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8180d3d0-ffffffff8180d6b7: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff81812e15-ffffffff81812f1b: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8183e4c0-ffffffff8183e7a7: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff8184403f-ffffffff81844145: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1061
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81913200-ffffffff8191341c: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff81916f92-ffffffff81917091: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1066
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8191a830-ffffffff8191aa2f: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff81c21eb4-ffffffff81c21fba: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1299
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff818fe5a0-ffffffff818fe8e9: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff81c1404a-ffffffff81c1412e: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1359
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8199d5f0-ffffffff8199da20: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff81d20f4b-ffffffff81d2102f: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1296
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81afa0c0-ffffffff81afa544: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff81eec9b0-ffffffff81eecac2: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81c883c0)
Location: drivers/usb/host/xhci-ring.c:1298
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81c883c0-ffffffff81c8895b: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81cef5e0)
Location: drivers/usb/host/xhci-ring.c:1320
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81cef5e0-ffffffff81cefb62: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da4e00)
Location: drivers/usb/host/xhci-ring.c:1328
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81da4e00-ffffffff81da5382: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a7d0c0)
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffff800010a7d0c0-ffff800010a7d510: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_handle_cmd_set_deq(struct xhci_hcd *xhci, int slot_id, union xhci_trb *trb, u32 cmd_comp_code);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b4f760)
Location: drivers/usb/host/xhci-ring.c:1035
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c0b4f760-c0b4fbb8: xhci_handle_cmd_set_deq (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c000000000b54890)
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c000000000b54890-c000000000b54da8: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffe0006938b4)
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffe0006938b4-ffffffe000693c94: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817f6870-ffffffff817f6b57: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff817fc3ef-ffffffff817fc4f5: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817bba10-ffffffff817bbcf7: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff817c158f-ffffffff817c1695: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81833340-ffffffff81833627: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff81838ebf-ffffffff81838fc5: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:1035
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8184d6d0-ffffffff8184d9e9: xhci_handle_cmd_set_deq.isra.0 (STB_LOCAL)
ffffffff8185331f-ffffffff81853421: xhci_handle_cmd_set_deq.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
