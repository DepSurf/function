# Function: <code>xhci_test_and_clear_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, __le32 **port_array, int port_id, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8165dbe0)
Location: drivers/usb/host/xhci-hub.c:570
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8165dbe0-ffffffff8165dc07: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, __le32 **port_array, int port_id, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff816bfc71)
Location: drivers/usb/host/xhci-hub.c:573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816be2e0-ffffffff816be307: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, __le32 **port_array, int port_id, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff816edbc0)
Location: drivers/usb/host/xhci-hub.c:573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816ec190-ffffffff816ec1b7: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, __le32 **port_array, int port_id, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8170254e)
Location: drivers/usb/host/xhci-hub.c:711
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817007c0-ffffffff817007e7: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, __le32 **port_array, int port_id, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8176f2a0)
Location: drivers/usb/host/xhci-hub.c:715
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8176d460-ffffffff8176d487: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817b028b)
Location: drivers/usb/host/xhci-hub.c:704
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff817ae1b0-ffffffff817ae1d0: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817d67d7)
Location: drivers/usb/host/xhci-hub.c:704
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff817d4580-ffffffff817d45a0: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81816c71)
Location: drivers/usb/host/xhci-hub.c:713
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81814950-ffffffff81814970: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81847fa1)
Location: drivers/usb/host/xhci-hub.c:722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81845b70-ffffffff81845b90: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8191a6b1)
Location: drivers/usb/host/xhci-hub.c:724
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81918a60-ffffffff81918a83: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8192100e)
Location: drivers/usb/host/xhci-hub.c:724
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff8191f3a0-ffffffff8191f3c3: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8190477e)
Location: drivers/usb/host/xhci-hub.c:810
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81902ac0-ffffffff81902ae0: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff819a4e8b)
Location: drivers/usb/host/xhci-hub.c:812
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff819a29a0-ffffffff819a29c0: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81b02886)
Location: drivers/usb/host/xhci-hub.c:813
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81b00490-ffffffff81b004ba: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81c918a6)
Location: drivers/usb/host/xhci-hub.c:827
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81c8f3e0-ffffffff81c8f40a: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81cf7fbe)
Location: drivers/usb/host/xhci-hub.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
ffffffff81cf6f70-ffffffff81cf6f9a: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81dad8ee)
Location: drivers/usb/host/xhci-hub.c:831
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
```
**Symbols:**

```
ffffffff81dac890-ffffffff81dac8ba: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffff800010a83e60)
Location: drivers/usb/host/xhci-hub.c:722
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffff800010a83e60-ffff800010a83ec4: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c0b59f48)
Location: drivers/usb/host/xhci-hub.c:722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
```
**Symbols:**

```
c0b57afc-c0b57b4c: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c000000000b5da30)
Location: drivers/usb/host/xhci-hub.c:722
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
c000000000b5da30-c000000000b5dae8: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffe00069c7d8)
Location: drivers/usb/host/xhci-hub.c:722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffe00069a668-ffffffe00069a6da: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81800351)
Location: drivers/usb/host/xhci-hub.c:722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff817fdf20-ffffffff817fdf40: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817c54f1)
Location: drivers/usb/host/xhci-hub.c:722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff817c30c0-ffffffff817c30e0: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8183ce21)
Location: drivers/usb/host/xhci-hub.c:722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff8183a9f0-ffffffff8183aa10: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xhci_test_and_clear_bit(struct xhci_hcd *xhci, struct xhci_port *port, u32 port_bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff818572f1)
Location: drivers/usb/host/xhci-hub.c:722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81854e80-ffffffff81854ea0: xhci_test_and_clear_bit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_port *port</code>
</li>
<li>
<b>Param removed. </b>
<code>__le32 **port_array</code>
</li>
<li>
<b>Param removed. </b>
<code>int port_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, port_array, port_id, port_bit</code> ➡️ <code>xhci, port, port_bit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
