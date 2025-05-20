# Function: <code>xhci_free_virt_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81655400)
Location: drivers/usb/host/xhci-mem.c:913
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81655400-ffffffff81655573: xhci_free_virt_device.part.31 (STB_LOCAL)
ffffffff81655580-ffffffff81655595: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b644c)
Location: drivers/usb/host/xhci-mem.c:928
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816b5e10-ffffffff816b5f86: xhci_free_virt_device.part.30 (STB_LOCAL)
ffffffff816b5f90-ffffffff816b5fa5: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e4471)
Location: drivers/usb/host/xhci-mem.c:928
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816e3fc0-ffffffff816e4136: xhci_free_virt_device.part.33 (STB_LOCAL)
ffffffff816e4140-ffffffff816e4155: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f841f)
Location: drivers/usb/host/xhci-mem.c:882
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
Direct callers:
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816f7f80-ffffffff816f8113: xhci_free_virt_device.part.40 (STB_LOCAL)
ffffffff816f8120-ffffffff816f8136: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81764e99)
Location: drivers/usb/host/xhci-mem.c:869
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81764ca0-ffffffff81764e2c: xhci_free_virt_device.part.38 (STB_LOCAL)
ffffffff81764e30-ffffffff81764e46: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a4fd0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817a4fd0-ffffffff817a518c: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cb2b0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817cb2b0-ffffffff817cb46c: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8180c8c5-ffffffff8180c8e2: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff8180b690-ffffffff8180b821: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8183d8c0-ffffffff8183d8dd: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff8183c650-ffffffff8183c7e1: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot
```
**Symbols:**

```
ffffffff8191012e-ffffffff8191014b: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff8190db70-ffffffff8190dd3c: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:886
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot
```
**Symbols:**

```
ffffffff81c217d6-ffffffff81c217f3: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff81915710-ffffffff819158cd: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:869
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81c13881-ffffffff81c1389e: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff818f8ba0-ffffffff818f8d5c: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:869
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d206c5-ffffffff81d206e2: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff81997370-ffffffff8199769b: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:860
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81eec245-ffffffff81eec262: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff81af4280-ffffffff81af45cf: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c81930)
Location: drivers/usb/host/xhci-mem.c:865
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c81930-ffffffff81c81cd9: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce8640)
Location: drivers/usb/host/xhci-mem.c:847
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81ce8640-ffffffff81ce89e9: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9de60)
Location: drivers/usb/host/xhci-mem.c:858
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d9de60-ffffffff81d9e209: xhci_free_virt_device (STB_GLOBAL)
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
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a7a488)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffff800010a7a488-ffff800010a7a63c: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4dd98)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c0b4dd98-c0b4df5c: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51dc0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c000000000b51dc0-c000000000b52008: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691b3e)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffe000691b3e-ffffffe000691cb4: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817f5c70-ffffffff817f5c8d: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff817f4a00-ffffffff817f4b91: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817bae10-ffffffff817bae2d: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff817b9ba0-ffffffff817b9d31: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81832740-ffffffff8183275d: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff818314d0-ffffffff81831661: xhci_free_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xhci_free_virt_device(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:877
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_devices_depth_first
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8184c920-ffffffff8184c93d: xhci_free_virt_device.cold (STB_LOCAL)
ffffffff8184b6a0-ffffffff8184b84a: xhci_free_virt_device (STB_GLOBAL)
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
