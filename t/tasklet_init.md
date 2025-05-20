# Function: <code>tasklet_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81084840)
Location: kernel/softirq.c:557
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
**Symbols:**

```
ffffffff81084840-ffffffff81084869: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810880ca)
Location: kernel/softirq.c:557
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
**Symbols:**

```
ffffffff810879a0-ffffffff810879c9: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d02a)
Location: kernel/softirq.c:571
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - net/core/flow.c:flow_cache_cpu_up_prep
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
**Symbols:**

```
ffffffff8108c900-ffffffff8108c929: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81089e27)
Location: kernel/softirq.c:571
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - net/core/flow.c:flow_cache_cpu_up_prep
  - net/ipv4/tcp_output.c:tcp_tasklet_init
```
**Symbols:**

```
ffffffff810899e0-ffffffff81089a09: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81090b67)
Location: kernel/softirq.c:561
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff81090760-ffffffff81090789: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81094717)
Location: kernel/softirq.c:548
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff81094380-ffffffff810943a9: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109ca77)
Location: kernel/softirq.c:549
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff8109c6a0-ffffffff8109c6c9: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a0d20)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff810a0d20-ffffffff810a0d49: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a72e0)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff810a72e0-ffffffff810a7309: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aea30)
Location: kernel/softirq.c:576
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff810aea30-ffffffff810aea59: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aa200)
Location: kernel/softirq.c:595
Inline: False
```
**Symbols:**

```
ffffffff810aa200-ffffffff810aa22d: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ab220)
Location: kernel/softirq.c:825
Inline: False
```
**Symbols:**

```
ffffffff810ab220-ffffffff810ab24d: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bcd40)
Location: kernel/softirq.c:824
Inline: False
```
**Symbols:**

```
ffffffff810bcd40-ffffffff810bcd6d: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d3bd0)
Location: kernel/softirq.c:838
Inline: False
```
**Symbols:**

```
ffffffff810d3bd0-ffffffff810d3c07: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f2960)
Location: kernel/softirq.c:838
Inline: False
```
**Symbols:**

```
ffffffff810f2960-ffffffff810f2997: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810fea20)
Location: kernel/softirq.c:825
Inline: False
```
**Symbols:**

```
ffffffff810fea20-ffffffff810fea57: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff811080d0)
Location: kernel/softirq.c:825
Inline: False
```
**Symbols:**

```
ffffffff811080d0-ffffffff81108107: tasklet_init (STB_GLOBAL)
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
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100fe5e8)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/dma/virt-dma.c:vchan_init
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffff8000100fe5e8-ffff8000100fe628: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035b2bc)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/dma/virt-dma.c:vchan_init
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - sound/core/timer.c:snd_timer_new
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
c035b2bc-c035b2ec: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c0000000001453c0)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
c0000000001453c0-c0000000001453e8: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c6748)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffe0000c6748-ffffffe0000c6788: tasklet_init (STB_GLOBAL)
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
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a0c00)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff810a0c00-ffffffff810a0c29: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108f620)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/hv/hv.c:hv_synic_alloc
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff8108f620-ffffffff8108f649: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a0bb0)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff810a0bb0-ffffffff810a0bd9: tasklet_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tasklet_init(struct tasklet_struct *t, void (*func)(long unsigned int), long unsigned int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a8b30)
Location: kernel/softirq.c:549
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/xfrm/xfrm_input.c:xfrm_input_init
```
**Symbols:**

```
ffffffff810a8b30-ffffffff810a8b59: tasklet_init (STB_GLOBAL)
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
