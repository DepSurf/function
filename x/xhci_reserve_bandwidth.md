# Function: <code>xhci_reserve_bandwidth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164eca0)
Location: drivers/usb/host/xhci.c:2544
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff8164eca0-ffffffff8164f40b: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816af5f0)
Location: drivers/usb/host/xhci.c:2522
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff816af5f0-ffffffff816afd79: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dd790)
Location: drivers/usb/host/xhci.c:2511
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff816dd790-ffffffff816ddf19: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f1790)
Location: drivers/usb/host/xhci.c:2455
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff816f1790-ffffffff816f1eb1: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175da10)
Location: drivers/usb/host/xhci.c:2466
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff8175da10-ffffffff8175e131: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179e3f0)
Location: drivers/usb/host/xhci.c:2592
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff8179e3f0-ffffffff8179eb7b: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c45e0)
Location: drivers/usb/host/xhci.c:2609
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817c45e0-ffffffff817c4d80: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2638
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81803db0-ffffffff8180443c: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff81807e29-ffffffff81807efb: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81834c80-ffffffff8183530c: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff81838d10-ffffffff81838de2: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2650
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81907b50-ffffffff81907e3f: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff8190b605-ffffffff8190b62f: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2783
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff819102f0-ffffffff819105df: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff81c21032-ffffffff81c2105c: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2778
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff818f38d0-ffffffff818f3bcf: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff81c1308f-ffffffff81c130b9: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2790
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81990b80-ffffffff819912d9: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff81d1fe64-ffffffff81d1fe8e: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2828
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81aed2c0-ffffffff81aedc6d: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff81eeb9e0-ffffffff81eeba05: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c79c60)
Location: drivers/usb/host/xhci.c:2826
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81c79c60-ffffffff81c7a5ef: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce0d50)
Location: drivers/usb/host/xhci.c:2666
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81ce0d50-ffffffff81ce1866: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d95ea0)
Location: drivers/usb/host/xhci.c:2696
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81d95ea0-ffffffff81d969b6: xhci_reserve_bandwidth (STB_LOCAL)
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
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a72660)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffff800010a72660-ffff800010a72c44: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b462e0)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
c0b462e0-c0b46900: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b47eb0)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
c000000000b47eb0-c000000000b485a0: xhci_reserve_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068ad36)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffe00068ad36-ffffffe00068b228: xhci_reserve_bandwidth (STB_LOCAL)
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
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817ed030-ffffffff817ed6bc: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff817f10c0-ffffffff817f1192: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff817b2140-ffffffff817b27cc: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff817b6256-ffffffff817b6328: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81829b00-ffffffff8182a18c: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff8182db90-ffffffff8182dc62: xhci_reserve_bandwidth.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_reserve_bandwidth(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, struct xhci_container_ctx *in_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2647
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
```
**Symbols:**

```
ffffffff81843aa0-ffffffff8184412c: xhci_reserve_bandwidth (STB_LOCAL)
ffffffff81847c79-ffffffff81847d4b: xhci_reserve_bandwidth.cold (STB_LOCAL)
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
