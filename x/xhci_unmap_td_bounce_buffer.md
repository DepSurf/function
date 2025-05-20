# Function: <code>xhci_unmap_td_bounce_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_unmap_td_bounce_buffer(struct xhci_hcd *xhci, struct xhci_ring *ring, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b8660)
Location: drivers/usb/host/xhci-ring.c:608
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff816b8660-ffffffff816b873b: xhci_unmap_td_bounce_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e6490)
Location: drivers/usb/host/xhci-ring.c:663
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff816e6490-ffffffff816e655e: xhci_unmap_td_bounce_buffer.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fa200)
Location: drivers/usb/host/xhci-ring.c:664
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff816fa200-ffffffff816fa2d9: xhci_unmap_td_bounce_buffer.isra.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81766c40)
Location: drivers/usb/host/xhci-ring.c:653
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81766c40-ffffffff81766d1f: xhci_unmap_td_bounce_buffer.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a7870)
Location: drivers/usb/host/xhci-ring.c:653
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817a7870-ffffffff817a7958: xhci_unmap_td_bounce_buffer.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817cd810)
Location: drivers/usb/host/xhci-ring.c:653
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817cd810-ffffffff817cd91b: xhci_unmap_td_bounce_buffer.isra.42 (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8180d890-ffffffff8180d98b: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81812f1b-ffffffff81812f36: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8183e980-ffffffff8183ea7b: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81844145-ffffffff81844160: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:682
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81910e70-ffffffff81910f6b: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81916aa5-ffffffff81916ac0: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:682
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81918610-ffffffff819186c1: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81c219ca-ffffffff81c219e5: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:739
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff818fb930-ffffffff818fb9dd: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81c13b1e-ffffffff81c13b39: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:775
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8199a7b0-ffffffff8199a85d: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81d209b2-ffffffff81d209cd: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:767
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81af78b0-ffffffff81af797f: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81eec52b-ffffffff81eec546: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81c85570)
Location: drivers/usb/host/xhci-ring.c:767
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81c85570-ffffffff81c85651: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81cebfe0)
Location: drivers/usb/host/xhci-ring.c:798
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81cebfe0-ffffffff81cec0c1: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da1600)
Location: drivers/usb/host/xhci-ring.c:806
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81da1600-ffffffff81da16e2: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a7c428)
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffff800010a7c428-ffff800010a7c554: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_unmap_td_bounce_buffer(struct xhci_hcd *xhci, struct xhci_ring *ring, struct xhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b5051c)
Location: drivers/usb/host/xhci-ring.c:660
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
c0b5051c-c0b50650: xhci_unmap_td_bounce_buffer (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c000000000b54ef0)
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
c000000000b54ef0-c000000000b550c0: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffe000693fc8)
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffe000693fc8-ffffffe0006940aa: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817f6d30-ffffffff817f6e2b: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff817fc4f5-ffffffff817fc510: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817bbed0-ffffffff817bbfcb: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff817c1695-ffffffff817c16b0: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81833800-ffffffff818338fb: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81838fc5-ffffffff81838fe0: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:660
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8184dad0-ffffffff8184dbcb: xhci_unmap_td_bounce_buffer.isra.0 (STB_LOCAL)
ffffffff81853421-ffffffff8185343c: xhci_unmap_td_bounce_buffer.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
