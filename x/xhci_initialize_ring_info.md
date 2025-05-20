# Function: <code>xhci_initialize_ring_info</code>

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
In drivers/usb/host/xhci-mem.c (ffffffff816530f8)
Location: drivers/usb/host/xhci-mem.c:290
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/host/xhci-mem.c (ffffffff816b53b0)
Location: drivers/usb/host/xhci-mem.c:300
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/host/xhci-mem.c (ffffffff816e3560)
Location: drivers/usb/host/xhci-mem.c:300
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/host/xhci-mem.c (ffffffff816f677a)
Location: drivers/usb/host/xhci-mem.c:302
Inline: True
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
In drivers/usb/host/xhci-mem.c (ffffffff81763123)
Location: drivers/usb/host/xhci-mem.c:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
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
In drivers/usb/host/xhci-mem.c (ffffffff817a336f)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
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
In drivers/usb/host/xhci-mem.c (ffffffff817c966a)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
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
In drivers/usb/host/xhci-mem.c (ffffffff81809a95)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
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
In drivers/usb/host/xhci-mem.c (ffffffff8183aa15)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190d425)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xhci_initialize_ring_info(struct xhci_ring *ring, unsigned int cycle_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81914eb5)
Location: drivers/usb/host/xhci-mem.c:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81914d80-ffffffff81914db4: xhci_initialize_ring_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_initialize_ring_info(struct xhci_ring *ring, unsigned int cycle_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f83d2)
Location: drivers/usb/host/xhci-mem.c:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff818f82a0-ffffffff818f82d4: xhci_initialize_ring_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_initialize_ring_info(struct xhci_ring *ring, unsigned int cycle_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81996a3b)
Location: drivers/usb/host/xhci-mem.c:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81996900-ffffffff81996934: xhci_initialize_ring_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xhci_initialize_ring_info(struct xhci_ring *ring, unsigned int cycle_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af3927)
Location: drivers/usb/host/xhci-mem.c:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81af37e0-ffffffff81af3820: xhci_initialize_ring_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xhci_initialize_ring_info(struct xhci_ring *ring, unsigned int cycle_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c80ed3)
Location: drivers/usb/host/xhci-mem.c:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81c80d80-ffffffff81c80dc0: xhci_initialize_ring_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xhci_initialize_ring_info(struct xhci_ring *ring, unsigned int cycle_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce7c13)
Location: drivers/usb/host/xhci-mem.c:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81ce7ac0-ffffffff81ce7b00: xhci_initialize_ring_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_initialize_ring_info(struct xhci_ring *ring, unsigned int cycle_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d047)
Location: drivers/usb/host/xhci-mem.c:303
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81d9b160-ffffffff81d9b1a0: xhci_initialize_ring_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a78484)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4c0b0)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4f7b8)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00069000a)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f2dc5)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b7f65)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182f895)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81849a05)
Location: drivers/usb/host/xhci-mem.c:293
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
