# Function: <code>xhci_alloc_streams</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81650390)
Location: drivers/usb/host/xhci.c:3150
Inline: False
```
**Symbols:**

```
ffffffff81650390-ffffffff81650bbd: xhci_alloc_streams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816b0cc0)
Location: drivers/usb/host/xhci.c:3129
Inline: False
```
**Symbols:**

```
ffffffff816b0cc0-ffffffff816b14fa: xhci_alloc_streams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dee70)
Location: drivers/usb/host/xhci.c:3118
Inline: False
```
**Symbols:**

```
ffffffff816dee70-ffffffff816df6aa: xhci_alloc_streams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f36d0)
Location: drivers/usb/host/xhci.c:3058
Inline: False
```
**Symbols:**

```
ffffffff816f36d0-ffffffff816f3ef2: xhci_alloc_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175f9a0)
Location: drivers/usb/host/xhci.c:3074
Inline: False
```
**Symbols:**

```
ffffffff8175f9a0-ffffffff817601aa: xhci_alloc_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817a0390)
Location: drivers/usb/host/xhci.c:3269
Inline: False
```
**Symbols:**

```
ffffffff817a0390-ffffffff817a0b6b: xhci_alloc_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c6650)
Location: drivers/usb/host/xhci.c:3286
Inline: False
```
**Symbols:**

```
ffffffff817c6650-ffffffff817c6e2b: xhci_alloc_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3327
Inline: False
```
**Symbols:**

```
ffffffff81805ac0-ffffffff8180621b: xhci_alloc_streams (STB_LOCAL)
ffffffff81808234-ffffffff81808328: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
ffffffff81836970-ffffffff818370cb: xhci_alloc_streams (STB_LOCAL)
ffffffff8183911b-ffffffff8183920f: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3401
Inline: False
```
**Symbols:**

```
ffffffff819092c0-ffffffff81909851: xhci_alloc_streams (STB_LOCAL)
ffffffff8190b93b-ffffffff8190b9b6: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3535
Inline: False
```
**Symbols:**

```
ffffffff81911a50-ffffffff819120ca: xhci_alloc_streams (STB_LOCAL)
ffffffff81c2134c-ffffffff81c213bf: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3462
Inline: False
```
**Symbols:**

```
ffffffff818f5050-ffffffff818f56df: xhci_alloc_streams (STB_LOCAL)
ffffffff81c13405-ffffffff81c13478: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3479
Inline: False
```
**Symbols:**

```
ffffffff81992d00-ffffffff81993617: xhci_alloc_streams (STB_LOCAL)
ffffffff81d201cc-ffffffff81d2025d: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3513
Inline: False
```
**Symbols:**

```
ffffffff81aef7d0-ffffffff81af00e1: xhci_alloc_streams (STB_LOCAL)
ffffffff81eebd25-ffffffff81eebdb1: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3511
Inline: False
```
**Symbols:**

```
ffffffff81c7c520-ffffffff81c7ce8f: xhci_alloc_streams (STB_LOCAL)
ffffffff820a57ab-ffffffff820a57c9: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3351
Inline: False
```
**Symbols:**

```
ffffffff81ce3790-ffffffff81ce40ff: xhci_alloc_streams (STB_LOCAL)
ffffffff82126c23-ffffffff82126c41: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3402
Inline: False
```
**Symbols:**

```
ffffffff81d988f0-ffffffff81d9925f: xhci_alloc_streams (STB_LOCAL)
ffffffff82208426-ffffffff82208444: xhci_alloc_streams.cold (STB_LOCAL)
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
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a74840)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
ffff800010a74840-ffff800010a750d0: xhci_alloc_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b482bc)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
c0b482bc-c0b48b44: xhci_alloc_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b4a900)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
c000000000b4a900-c000000000b4b2f8: xhci_alloc_streams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068c9e2)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
ffffffe00068c9e2-ffffffe00068d1f2: xhci_alloc_streams (STB_LOCAL)
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
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
ffffffff817eed20-ffffffff817ef47b: xhci_alloc_streams (STB_LOCAL)
ffffffff817f14cb-ffffffff817f15bf: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
ffffffff817b3e30-ffffffff817b458b: xhci_alloc_streams (STB_LOCAL)
ffffffff817b6661-ffffffff817b6755: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
ffffffff8182b7f0-ffffffff8182bf4b: xhci_alloc_streams (STB_LOCAL)
ffffffff8182df9b-ffffffff8182e08f: xhci_alloc_streams.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_streams(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint **eps, unsigned int num_eps, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3397
Inline: False
```
**Symbols:**

```
ffffffff818457c0-ffffffff81845f1b: xhci_alloc_streams (STB_LOCAL)
ffffffff81848081-ffffffff81848175: xhci_alloc_streams.cold (STB_LOCAL)
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
