# Function: <code>xhci_update_hub_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81651900)
Location: drivers/usb/host/xhci.c:4739
Inline: False
```
**Symbols:**

```
ffffffff81651900-ffffffff81651d22: xhci_update_hub_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816b2210)
Location: drivers/usb/host/xhci.c:4721
Inline: False
```
**Symbols:**

```
ffffffff816b2210-ffffffff816b260a: xhci_update_hub_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816e03c0)
Location: drivers/usb/host/xhci.c:4714
Inline: False
```
**Symbols:**

```
ffffffff816e03c0-ffffffff816e07ba: xhci_update_hub_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f2d00)
Location: drivers/usb/host/xhci.c:4664
Inline: False
```
**Symbols:**

```
ffffffff816f2d00-ffffffff816f3053: xhci_update_hub_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175efd0)
Location: drivers/usb/host/xhci.c:4671
Inline: False
```
**Symbols:**

```
ffffffff8175efd0-ffffffff8175f323: xhci_update_hub_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179f9d0)
Location: drivers/usb/host/xhci.c:4856
Inline: False
```
**Symbols:**

```
ffffffff8179f9d0-ffffffff8179fd1c: xhci_update_hub_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c5c90)
Location: drivers/usb/host/xhci.c:4888
Inline: False
```
**Symbols:**

```
ffffffff817c5c90-ffffffff817c5fdc: xhci_update_hub_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4933
Inline: False
```
**Symbols:**

```
ffffffff818051e0-ffffffff818054eb: xhci_update_hub_device (STB_LOCAL)
ffffffff81808129-ffffffff8180817d: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
ffffffff81836090-ffffffff8183639b: xhci_update_hub_device (STB_LOCAL)
ffffffff81839010-ffffffff81839064: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5016
Inline: False
```
**Symbols:**

```
ffffffff81908a00-ffffffff81908d0b: xhci_update_hub_device (STB_LOCAL)
ffffffff8190b88d-ffffffff8190b8e1: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5154
Inline: False
```
**Symbols:**

```
ffffffff81911440-ffffffff8191174b: xhci_update_hub_device (STB_LOCAL)
ffffffff81c212f8-ffffffff81c2134c: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5081
Inline: False
```
**Symbols:**

```
ffffffff818f4a30-ffffffff818f4d3b: xhci_update_hub_device (STB_LOCAL)
ffffffff81c13355-ffffffff81c133a9: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5101
Inline: False
```
**Symbols:**

```
ffffffff81992380-ffffffff819926ac: xhci_update_hub_device (STB_LOCAL)
ffffffff81d2011c-ffffffff81d20170: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5123
Inline: False
```
**Symbols:**

```
ffffffff81aeee10-ffffffff81aef130: xhci_update_hub_device (STB_LOCAL)
ffffffff81eebc7c-ffffffff81eebcc9: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c7b1f0)
Location: drivers/usb/host/xhci.c:5135
Inline: False
```
**Symbols:**

```
ffffffff81c7b1f0-ffffffff81c7b55a: xhci_update_hub_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce2460)
Location: drivers/usb/host/xhci.c:4969
Inline: False
```
**Symbols:**

```
ffffffff81ce2460-ffffffff81ce27ca: xhci_update_hub_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d975b0)
Location: drivers/usb/host/xhci.c:5029
Inline: False
```
**Symbols:**

```
ffffffff81d975b0-ffffffff81d9791a: xhci_update_hub_device (STB_GLOBAL)
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
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a73d40)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
ffff800010a73d40-ffff800010a74100: xhci_update_hub_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b478e4)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
c0b478e4-c0b47c38: xhci_update_hub_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b49c30)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
c000000000b49c30-c000000000b4a0a4: xhci_update_hub_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068c0ee)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
ffffffe00068c0ee-ffffffe00068c412: xhci_update_hub_device (STB_LOCAL)
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
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
ffffffff817ee440-ffffffff817ee74b: xhci_update_hub_device (STB_LOCAL)
ffffffff817f13c0-ffffffff817f1414: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
ffffffff817b3550-ffffffff817b385b: xhci_update_hub_device (STB_LOCAL)
ffffffff817b6556-ffffffff817b65aa: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
ffffffff8182af10-ffffffff8182b21b: xhci_update_hub_device (STB_LOCAL)
ffffffff8182de90-ffffffff8182dee4: xhci_update_hub_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_update_hub_device(struct usb_hcd *hcd, struct usb_device *hdev, struct usb_tt *tt, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5006
Inline: False
```
**Symbols:**

```
ffffffff81844ee0-ffffffff818451eb: xhci_update_hub_device (STB_LOCAL)
ffffffff81847f76-ffffffff81847fca: xhci_update_hub_device.cold (STB_LOCAL)
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
