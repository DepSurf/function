# Function: <code>xhci_free_streams</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81650bc0)
Location: drivers/usb/host/xhci.c:3311
Inline: False
```
**Symbols:**

```
ffffffff81650bc0-ffffffff81650f3e: xhci_free_streams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816b1500)
Location: drivers/usb/host/xhci.c:3293
Inline: False
```
**Symbols:**

```
ffffffff816b1500-ffffffff816b1890: xhci_free_streams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816df6b0)
Location: drivers/usb/host/xhci.c:3282
Inline: False
```
**Symbols:**

```
ffffffff816df6b0-ffffffff816dfa40: xhci_free_streams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f3340)
Location: drivers/usb/host/xhci.c:3221
Inline: False
```
**Symbols:**

```
ffffffff816f3340-ffffffff816f36cc: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175f610)
Location: drivers/usb/host/xhci.c:3237
Inline: False
```
**Symbols:**

```
ffffffff8175f610-ffffffff8175f999: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817a0000)
Location: drivers/usb/host/xhci.c:3432
Inline: False
```
**Symbols:**

```
ffffffff817a0000-ffffffff817a0382: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c62c0)
Location: drivers/usb/host/xhci.c:3449
Inline: False
```
**Symbols:**

```
ffffffff817c62c0-ffffffff817c6642: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3490
Inline: False
```
**Symbols:**

```
ffffffff81805780-ffffffff81805ab1: xhci_free_streams (STB_LOCAL)
ffffffff818081d8-ffffffff81808234: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
ffffffff81836630-ffffffff81836961: xhci_free_streams (STB_LOCAL)
ffffffff818390bf-ffffffff8183911b: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81908fc0)
Location: drivers/usb/host/xhci.c:3564
Inline: False
```
**Symbols:**

```
ffffffff81908fc0-ffffffff819092bd: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81911750)
Location: drivers/usb/host/xhci.c:3702
Inline: False
```
**Symbols:**

```
ffffffff81911750-ffffffff81911a4e: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3629
Inline: False
```
**Symbols:**

```
ffffffff818f4d40-ffffffff818f504c: xhci_free_streams (STB_LOCAL)
ffffffff81c133a9-ffffffff81c13405: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3646
Inline: False
```
**Symbols:**

```
ffffffff819926b0-ffffffff81992cfe: xhci_free_streams (STB_LOCAL)
ffffffff81d20170-ffffffff81d201cc: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3680
Inline: False
```
**Symbols:**

```
ffffffff81aef130-ffffffff81aef7cd: xhci_free_streams (STB_LOCAL)
ffffffff81eebcc9-ffffffff81eebd25: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c7be50)
Location: drivers/usb/host/xhci.c:3678
Inline: False
```
**Symbols:**

```
ffffffff81c7be50-ffffffff81c7c507: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce30c0)
Location: drivers/usb/host/xhci.c:3518
Inline: False
```
**Symbols:**

```
ffffffff81ce30c0-ffffffff81ce3777: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d98220)
Location: drivers/usb/host/xhci.c:3569
Inline: False
```
**Symbols:**

```
ffffffff81d98220-ffffffff81d988d7: xhci_free_streams (STB_LOCAL)
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
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a743f0)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
ffff800010a743f0-ffff800010a74840: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b47f28)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
c0b47f28-c0b482bc: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b4a460)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
c000000000b4a460-c000000000b4a900: xhci_free_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068c688)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
ffffffe00068c688-ffffffe00068c9e2: xhci_free_streams (STB_LOCAL)
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
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
ffffffff817ee9e0-ffffffff817eed11: xhci_free_streams (STB_LOCAL)
ffffffff817f146f-ffffffff817f14cb: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
ffffffff817b3af0-ffffffff817b3e21: xhci_free_streams (STB_LOCAL)
ffffffff817b6605-ffffffff817b6661: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
ffffffff8182b4b0-ffffffff8182b7e1: xhci_free_streams (STB_LOCAL)
ffffffff8182df3f-ffffffff8182df9b: xhci_free_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_free_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3560
Inline: False
```
**Symbols:**

```
ffffffff81845480-ffffffff818457b1: xhci_free_streams (STB_LOCAL)
ffffffff81848025-ffffffff81848081: xhci_free_streams.cold (STB_LOCAL)
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
