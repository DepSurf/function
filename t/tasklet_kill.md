# Function: <code>tasklet_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81084d20)
Location: kernel/softirq.c:568
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff81084d20-ffffffff81084d8e: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81088040)
Location: kernel/softirq.c:568
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff81088040-ffffffff81088099: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108cfa0)
Location: kernel/softirq.c:582
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff8108cfa0-ffffffff8108cff9: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81089da0)
Location: kernel/softirq.c:582
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff81089da0-ffffffff81089df9: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81090ae0)
Location: kernel/softirq.c:572
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff81090ae0-ffffffff81090b39: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:559
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff8109549d-ffffffff810954ae: tasklet_kill.cold.20 (STB_LOCAL)
ffffffff81094880-ffffffff810948cf: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:560
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff8109d81d-ffffffff8109d82e: tasklet_kill.cold.22 (STB_LOCAL)
ffffffff8109cbe0-ffffffff8109cc2f: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff810a1ddd-ffffffff810a1dee: tasklet_kill.cold (STB_LOCAL)
ffffffff810a10f0-ffffffff810a114e: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff810a839d-ffffffff810a83ae: tasklet_kill.cold (STB_LOCAL)
ffffffff810a76b0-ffffffff810a770e: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:587
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff810afc8d-ffffffff810afc9e: tasklet_kill.cold (STB_LOCAL)
ffffffff810aedc0-ffffffff810aee1e: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:607
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81bdb7ee-ffffffff81bdb7ff: tasklet_kill.cold (STB_LOCAL)
ffffffff810aa590-ffffffff810aa5ee: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:863
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81bcd8e0-ffffffff81bcd8f1: tasklet_kill.cold (STB_LOCAL)
ffffffff810ab7c0-ffffffff810ab88a: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:862
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81ca4294-ffffffff81ca42a5: tasklet_kill.cold (STB_LOCAL)
ffffffff810bd210-ffffffff810bd2da: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:876
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81e53b26-ffffffff81e53b37: tasklet_kill.cold (STB_LOCAL)
ffffffff810d4350-ffffffff810d443e: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f31e0)
Location: kernel/softirq.c:876
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_remove
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff810f31e0-ffffffff810f32e3: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ff520)
Location: kernel/softirq.c:863
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_remove
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff810ff520-ffffffff810ff623: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81108bd0)
Location: kernel/softirq.c:863
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_remove
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81108bd0-ffffffff81108cd3: tasklet_kill (STB_GLOBAL)
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
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100fe938)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_free
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/net/ethernet/smsc/smc91x.c:smc_close
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffff8000100fe938-ffff8000100fea38: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035b7b4)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_remove
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/ti/edma.c:edma_remove
  - drivers/dma/ti/edma.c:edma_synchronize
  - drivers/dma/ti/omap-dma.c:omap_dma_free
  - drivers/dma/ti/omap-dma.c:omap_dma_synchronize
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c035b7b4-c035b848: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c000000000145b10)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c000000000145b10-c000000000145c28: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c6cd8)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffe0000c6cd8-ffffffe0000c6d62: tasklet_kill (STB_GLOBAL)
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
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:560
Inline: False
```
**Symbols:**

```
ffffffff810a1cbd-ffffffff810a1cce: tasklet_kill.cold (STB_LOCAL)
ffffffff810a0fd0-ffffffff810a102e: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - drivers/hv/channel_mgmt.c:vmbus_add_channel_work
  - drivers/hv/channel_mgmt.c:hv_process_channel_removal
```
**Symbols:**

```
ffffffff8109069d-ffffffff810906ae: tasklet_kill.cold (STB_LOCAL)
ffffffff8108f9f0-ffffffff8108fa4e: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff810a1c6d-ffffffff810a1c7e: tasklet_kill.cold (STB_LOCAL)
ffffffff810a0f80-ffffffff810a0fde: tasklet_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tasklet_kill(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:560
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff810a9c8d-ffffffff810a9c9e: tasklet_kill.cold (STB_LOCAL)
ffffffff810a8f00-ffffffff810a8f5e: tasklet_kill (STB_GLOBAL)
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
