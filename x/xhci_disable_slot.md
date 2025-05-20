# Function: <code>xhci_disable_slot</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, struct xhci_command *command, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f46b0)
Location: drivers/usb/host/xhci.c:3564
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff816f46b0-ffffffff816f47de: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81760970)
Location: drivers/usb/host/xhci.c:3572
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81760970-ffffffff81760a45: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817a13b0)
Location: drivers/usb/host/xhci.c:3765
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817a13b0-ffffffff817a1483: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c7670)
Location: drivers/usb/host/xhci.c:3782
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817c7670-ffffffff817c7743: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818069b0)
Location: drivers/usb/host/xhci.c:3824
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff818069b0-ffffffff81806a87: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81837860)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81837860-ffffffff81837942: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81909f50)
Location: drivers/usb/host/xhci.c:3897
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81909f50-ffffffff8190a032: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff819127b0)
Location: drivers/usb/host/xhci.c:4035
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff819127b0-ffffffff81912892: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f5c90)
Location: drivers/usb/host/xhci.c:3962
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff818f5c90-ffffffff818f5d75: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3976
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d202c0-ffffffff81d202e1: xhci_disable_slot.cold (STB_LOCAL)
ffffffff81993db0-ffffffff81993ed1: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4008
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81eebe0e-ffffffff81eebe28: xhci_disable_slot.cold (STB_LOCAL)
ffffffff81af08c0-ffffffff81af09db: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c7d730)
Location: drivers/usb/host/xhci.c:4011
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c7d730-ffffffff81c7d85e: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce49a0)
Location: drivers/usb/host/xhci.c:3851
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81ce49a0-ffffffff81ce4ace: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d99a10)
Location: drivers/usb/host/xhci.c:3902
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d99a10-ffffffff81d99b3e: xhci_disable_slot (STB_GLOBAL)
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
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a75950)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffff800010a75950-ffff800010a75ad0: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b49408)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c0b49408-c0b494ec: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b4bce0)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c000000000b4bce0-c000000000b4be7c: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068d99e)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffe00068d99e-ffffffe00068da84: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817efc10)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817efc10-ffffffff817efcf2: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b4d20)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817b4d20-ffffffff817b4e02: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8182c6e0)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8182c6e0-ffffffff8182c7c2: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_disable_slot(struct xhci_hcd *xhci, u32 slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818466d0)
Location: drivers/usb/host/xhci.c:3893
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff818466d0-ffffffff818467b2: xhci_disable_slot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct xhci_command *command</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, command, slot_id</code> ➡️ <code>xhci, slot_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
