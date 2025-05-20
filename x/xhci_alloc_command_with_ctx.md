# Function: <code>xhci_alloc_command_with_ctx</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a49e0)
Location: drivers/usb/host/xhci-mem.c:1758
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff817a49e0-ffffffff817a4a3c: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cadb0)
Location: drivers/usb/host/xhci-mem.c:1758
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff817cadb0-ffffffff817cae0c: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b160)
Location: drivers/usb/host/xhci-mem.c:1758
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff8180b160-ffffffff8180b1c1: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c120)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff8183c120-ffffffff8183c181: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190eef0)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff8190eef0-ffffffff8190ef51: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916a50)
Location: drivers/usb/host/xhci-mem.c:1772
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81916a50-ffffffff81916ab1: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f9ed0)
Location: drivers/usb/host/xhci-mem.c:1759
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff818f9ed0-ffffffff818f9f31: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81998bf0)
Location: drivers/usb/host/xhci-mem.c:1759
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81998bf0-ffffffff81998c51: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af5bf0)
Location: drivers/usb/host/xhci-mem.c:1750
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81af5bf0-ffffffff81af5c56: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c83500)
Location: drivers/usb/host/xhci-mem.c:1759
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81c83500-ffffffff81c83566: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81cea240)
Location: drivers/usb/host/xhci-mem.c:1739
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81cea240-ffffffff81cea2a6: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9fab0)
Location: drivers/usb/host/xhci-mem.c:1749
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81d9fab0-ffffffff81d9fb16: xhci_alloc_command_with_ctx (STB_GLOBAL)
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
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a79ee8)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffff800010a79ee8-ffff800010a79f68: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4d894)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
c0b4d894-c0b4d8fc: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51680)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
c000000000b51680-c000000000b51720: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00069165c)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffe00069165c-ffffffe0006916c6: xhci_alloc_command_with_ctx (STB_GLOBAL)
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
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f44d0)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff817f44d0-ffffffff817f4531: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9670)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff817b9670-ffffffff817b96d1: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81830fa0)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81830fa0-ffffffff81831001: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command_with_ctx(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b170)
Location: drivers/usb/host/xhci-mem.c:1764
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff8184b170-ffffffff8184b1d1: xhci_alloc_command_with_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
