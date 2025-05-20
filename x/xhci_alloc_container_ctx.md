# Function: <code>xhci_alloc_container_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81653160)
Location: drivers/usb/host/xhci-mem.c:503
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81653160-ffffffff8165323e: xhci_alloc_container_ctx.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b37b0)
Location: drivers/usb/host/xhci-mem.c:516
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff816b37b0-ffffffff816b388a: xhci_alloc_container_ctx.isra.26 (STB_LOCAL)
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
In drivers/usb/host/xhci-mem.c (ffffffff816e1960)
Location: drivers/usb/host/xhci-mem.c:516
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff816e1960-ffffffff816e1a3a: xhci_alloc_container_ctx.isra.29 (STB_LOCAL)
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
In drivers/usb/host/xhci-mem.c (ffffffff816f5b80)
Location: drivers/usb/host/xhci-mem.c:470
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff816f5b80-ffffffff816f5c3e: xhci_alloc_container_ctx.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817633e0)
Location: drivers/usb/host/xhci-mem.c:457
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817633e0-ffffffff817634b2: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a3630)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817a3630-ffffffff817a3710: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c9940)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817c9940-ffffffff817c9a21: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81809d60)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81809d60-ffffffff81809e4c: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183ace0)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff8183ace0-ffffffff8183adcc: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190d710)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff8190d710-ffffffff8190d7fc: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819152b0)
Location: drivers/usb/host/xhci-mem.c:469
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff819152b0-ffffffff8191539c: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f87c0)
Location: drivers/usb/host/xhci-mem.c:469
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff818f87c0-ffffffff818f88af: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81996ed0)
Location: drivers/usb/host/xhci-mem.c:469
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81996ed0-ffffffff81997008: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af3d80)
Location: drivers/usb/host/xhci-mem.c:468
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81af3d80-ffffffff81af3eb1: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c81370)
Location: drivers/usb/host/xhci-mem.c:468
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81c81370-ffffffff81c814a2: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce8080)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81ce8080-ffffffff81ce81b2: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d880)
Location: drivers/usb/host/xhci-mem.c:471
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81d9d880-ffffffff81d9d9cd: xhci_alloc_container_ctx (STB_GLOBAL)
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
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a787f0)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffff800010a787f0-ffff800010a788f8: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4c424)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
c0b4c424-c0b4c504: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4fc20)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
c000000000b4fc20-c000000000b4fd84: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe0006902c8)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffe0006902c8-ffffffe00069039c: xhci_alloc_container_ctx (STB_GLOBAL)
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
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f3090)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff817f3090-ffffffff817f317c: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b8230)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff817b8230-ffffffff817b831c: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182fb60)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff8182fb60-ffffffff8182fc4c: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xhci_container_ctx *xhci_alloc_container_ctx(struct xhci_hcd *xhci, int type, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81849d00)
Location: drivers/usb/host/xhci-mem.c:460
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
**Symbols:**

```
ffffffff81849d00-ffffffff81849dec: xhci_alloc_container_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
