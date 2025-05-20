# Function: <code>scratchpad_alloc</code>

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
In drivers/usb/host/xhci-mem.c (ffffffff81656587)
Location: drivers/usb/host/xhci-mem.c:1628
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff816b6fd5)
Location: drivers/usb/host/xhci-mem.c:1644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff816e527c)
Location: drivers/usb/host/xhci-mem.c:1677
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff816f91bb)
Location: drivers/usb/host/xhci-mem.c:1629
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff81765ccb)
Location: drivers/usb/host/xhci-mem.c:1631
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff817a6003)
Location: drivers/usb/host/xhci-mem.c:1644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff817cc0a9)
Location: drivers/usb/host/xhci-mem.c:1644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff8180c462)
Location: drivers/usb/host/xhci-mem.c:1644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff8183d454)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190cc50)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8190cc50-ffffffff8190ceb5: scratchpad_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819146a0)
Location: drivers/usb/host/xhci-mem.c:1658
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff819146a0-ffffffff81914905: scratchpad_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f7bd0)
Location: drivers/usb/host/xhci-mem.c:1645
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff818f7bd0-ffffffff818f7e35: scratchpad_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819961a0)
Location: drivers/usb/host/xhci-mem.c:1645
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff819961a0-ffffffff81996446: scratchpad_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af3090)
Location: drivers/usb/host/xhci-mem.c:1636
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81af3090-ffffffff81af3340: scratchpad_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c805a0)
Location: drivers/usb/host/xhci-mem.c:1645
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81c805a0-ffffffff81c8084e: scratchpad_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce7280)
Location: drivers/usb/host/xhci-mem.c:1626
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81ce7280-ffffffff81ce752e: scratchpad_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scratchpad_alloc(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9c6c0)
Location: drivers/usb/host/xhci-mem.c:1634
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81d9c6c0-ffffffff81d9c98a: scratchpad_alloc (STB_LOCAL)
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
In drivers/usb/host/xhci-mem.c (ffff800010a7b2b8)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (c0b4ebec)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (c000000000b53024)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffe000692954)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff817f5804)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff817ba9a4)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff818322d4)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff8184c4b4)
Location: drivers/usb/host/xhci-mem.c:1650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
