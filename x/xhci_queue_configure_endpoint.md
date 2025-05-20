# Function: <code>xhci_queue_configure_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81659f00)
Location: drivers/usb/host/xhci-ring.c:4068
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81659f00-ffffffff81659f33: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816bb240)
Location: drivers/usb/host/xhci-ring.c:3967
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff816ba6a0-ffffffff816ba6d3: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e9535)
Location: drivers/usb/host/xhci-ring.c:3867
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff816e8910-ffffffff816e8943: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fda09)
Location: drivers/usb/host/xhci-ring.c:3967
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff816fcb90-ffffffff816fcbbd: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8176a598)
Location: drivers/usb/host/xhci-ring.c:3971
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81769710-ffffffff8176973d: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817ab771)
Location: drivers/usb/host/xhci-ring.c:3890
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817aa9d0-ffffffff817aa9fd: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d17d7)
Location: drivers/usb/host/xhci-ring.c:3954
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817d0980-ffffffff817d09ad: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81811534)
Location: drivers/usb/host/xhci-ring.c:4020
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81810710-ffffffff8181073d: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81842725)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81841900-ffffffff8184192d: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8191308e)
Location: drivers/usb/host/xhci-ring.c:4095
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81915b10-ffffffff81915b3d: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8191a6d2)
Location: drivers/usb/host/xhci-ring.c:4124
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff8191d100-ffffffff8191d12d: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81901560)
Location: drivers/usb/host/xhci-ring.c:4318
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81901560-ffffffff8190158c: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff819a0e30)
Location: drivers/usb/host/xhci-ring.c:4388
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff819a0e30-ffffffff819a0e5c: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81afe650)
Location: drivers/usb/host/xhci-ring.c:4323
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81afe650-ffffffff81afe68e: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8d450)
Location: drivers/usb/host/xhci-ring.c:4330
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81c8d450-ffffffff81c8d48e: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf3fc0)
Location: drivers/usb/host/xhci-ring.c:4348
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81cf3fc0-ffffffff81cf3ffd: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da9900)
Location: drivers/usb/host/xhci-ring.c:4391
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81da9900-ffffffff81da993d: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a81660)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffff800010a806f8-ffff800010a80760: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b54a10)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
c0b53a6c-c0b53aa4: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5a99c)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
c000000000b59590-c000000000b595bc: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000697c44)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffe000696f82-ffffffe000696fdc: xhci_queue_configure_endpoint (STB_GLOBAL)
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
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817faad5)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817f9cb0-ffffffff817f9cdd: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bfc75)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817bee50-ffffffff817bee7d: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818375a5)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81836780-ffffffff818367ad: xhci_queue_configure_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_configure_endpoint(struct xhci_hcd *xhci, struct xhci_command *cmd, dma_addr_t in_ctx_ptr, u32 slot_id, bool command_must_succeed);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818519bf)
Location: drivers/usb/host/xhci-ring.c:4049
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
Direct callers:
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81850b00-ffffffff81850b2d: xhci_queue_configure_endpoint (STB_GLOBAL)
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
