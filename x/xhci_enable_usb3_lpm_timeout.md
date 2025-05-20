# Function: <code>xhci_enable_usb3_lpm_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816514e0)
Location: drivers/usb/host/xhci.c:4663
Inline: False
```
**Symbols:**

```
ffffffff816514e0-ffffffff81651872: xhci_enable_usb3_lpm_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816b1e40)
Location: drivers/usb/host/xhci.c:4645
Inline: False
```
**Symbols:**

```
ffffffff816b1e40-ffffffff816b218f: xhci_enable_usb3_lpm_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dfff0)
Location: drivers/usb/host/xhci.c:4638
Inline: False
```
**Symbols:**

```
ffffffff816dfff0-ffffffff816e033f: xhci_enable_usb3_lpm_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f2620)
Location: drivers/usb/host/xhci.c:4588
Inline: False
```
**Symbols:**

```
ffffffff816f2620-ffffffff816f2921: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175e900)
Location: drivers/usb/host/xhci.c:4595
Inline: False
```
**Symbols:**

```
ffffffff8175e900-ffffffff8175ec01: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179f350)
Location: drivers/usb/host/xhci.c:4780
Inline: False
```
**Symbols:**

```
ffffffff8179f350-ffffffff8179f614: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c55b0)
Location: drivers/usb/host/xhci.c:4812
Inline: False
```
**Symbols:**

```
ffffffff817c55b0-ffffffff817c58df: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4857
Inline: False
```
**Symbols:**

```
ffffffff81804af0-ffffffff81804e1e: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
ffffffff81808108-ffffffff81808129: xhci_enable_usb3_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
ffffffff818359c0-ffffffff81835cc5: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
ffffffff81838fef-ffffffff81839010: xhci_enable_usb3_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81908520)
Location: drivers/usb/host/xhci.c:4940
Inline: False
```
**Symbols:**

```
ffffffff81908520-ffffffff819085c8: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81910f60)
Location: drivers/usb/host/xhci.c:5078
Inline: False
```
**Symbols:**

```
ffffffff81910f60-ffffffff81911008: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f4550)
Location: drivers/usb/host/xhci.c:5005
Inline: False
```
**Symbols:**

```
ffffffff818f4550-ffffffff818f45ed: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81991e00)
Location: drivers/usb/host/xhci.c:5025
Inline: False
```
**Symbols:**

```
ffffffff81991e00-ffffffff81991ee0: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81aee810)
Location: drivers/usb/host/xhci.c:5044
Inline: False
```
**Symbols:**

```
ffffffff81aee810-ffffffff81aee962: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c7b810)
Location: drivers/usb/host/xhci.c:5048
Inline: False
```
**Symbols:**

```
ffffffff81c7b810-ffffffff81c7b9a5: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce2a90)
Location: drivers/usb/host/xhci.c:4882
Inline: False
```
**Symbols:**

```
ffffffff81ce2a90-ffffffff81ce2c1d: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d97be0)
Location: drivers/usb/host/xhci.c:4942
Inline: False
```
**Symbols:**

```
ffffffff81d97be0-ffffffff81d97d6d: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
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
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a735f8)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
ffff800010a735f8-ffff800010a73904: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b4721c)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
c0b4721c-c0b47554: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b49210)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
c000000000b49210-c000000000b49664: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068b9f2)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
ffffffe00068b9f2-ffffffe00068bcc2: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
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
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
ffffffff817edd70-ffffffff817ee075: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
ffffffff817f139f-ffffffff817f13c0: xhci_enable_usb3_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
ffffffff817b2e80-ffffffff817b3185: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
ffffffff817b6535-ffffffff817b6556: xhci_enable_usb3_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
ffffffff8182a840-ffffffff8182ab45: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
ffffffff8182de6f-ffffffff8182de90: xhci_enable_usb3_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_enable_usb3_lpm_timeout(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4930
Inline: False
```
**Symbols:**

```
ffffffff81844810-ffffffff81844b15: xhci_enable_usb3_lpm_timeout (STB_LOCAL)
ffffffff81847f55-ffffffff81847f76: xhci_enable_usb3_lpm_timeout.cold (STB_LOCAL)
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
