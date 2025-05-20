# Function: <code>ehci_endpoint_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8163b140)
Location: drivers/usb/host/ehci-hcd.c:943
Inline: False
```
**Symbols:**

```
ffffffff8163b140-ffffffff8163b326: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8169bdc0)
Location: drivers/usb/host/ehci-hcd.c:957
Inline: False
```
**Symbols:**

```
ffffffff8169bdc0-ffffffff8169bfd8: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c9ee0)
Location: drivers/usb/host/ehci-hcd.c:957
Inline: False
```
**Symbols:**

```
ffffffff816c9ee0-ffffffff816ca0f8: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816de0c0)
Location: drivers/usb/host/ehci-hcd.c:957
Inline: False
```
**Symbols:**

```
ffffffff816de0c0-ffffffff816de29b: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8174a800)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff8174a800-ffffffff8174a9e1: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8178a740)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff8178a740-ffffffff8178a91e: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817ac3e0)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff817ac3e0-ffffffff817ac5cf: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff817eb5f0-ffffffff817eb76d: ehci_endpoint_disable (STB_LOCAL)
ffffffff817f2a6a-ffffffff817f2adb: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff8181c4c0-ffffffff8181c63f: ehci_endpoint_disable (STB_LOCAL)
ffffffff8182391c-ffffffff81823957: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:945
Inline: False
```
**Symbols:**

```
ffffffff818f2de0-ffffffff818f2f6a: ehci_endpoint_disable (STB_LOCAL)
ffffffff818f557b-ffffffff818f55b5: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:957
Inline: False
```
**Symbols:**

```
ffffffff818fbd00-ffffffff818fbe8a: ehci_endpoint_disable (STB_LOCAL)
ffffffff81c2027c-ffffffff81c202b6: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:960
Inline: False
```
**Symbols:**

```
ffffffff818dea70-ffffffff818dec5b: ehci_endpoint_disable (STB_LOCAL)
ffffffff81c122e5-ffffffff81c12320: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:970
Inline: False
```
**Symbols:**

```
ffffffff8197a630-ffffffff8197a81b: ehci_endpoint_disable (STB_LOCAL)
ffffffff81d1ec95-ffffffff81d1ecd0: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:970
Inline: False
```
**Symbols:**

```
ffffffff81ad7e30-ffffffff81ad8037: ehci_endpoint_disable (STB_LOCAL)
ffffffff81eea7e8-ffffffff81eea825: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c62a10)
Location: drivers/usb/host/ehci-hcd.c:970
Inline: False
```
**Symbols:**

```
ffffffff81c62a10-ffffffff81c62bea: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc9e00)
Location: drivers/usb/host/ehci-hcd.c:970
Inline: False
```
**Symbols:**

```
ffffffff81cc9e00-ffffffff81cc9fd7: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7ece0)
Location: drivers/usb/host/ehci-hcd.c:974
Inline: False
```
**Symbols:**

```
ffffffff81d7ece0-ffffffff81d7eeb7: ehci_endpoint_disable (STB_LOCAL)
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
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a56eb0)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffff800010a56eb0-ffff800010a570fc: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b28ba4)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
c0b28ba4-c0b28da0: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b22f60)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
c000000000b22f60-c000000000b231d8: ehci_endpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe0006753b4)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffe0006753b4-ffffffe000675548: ehci_endpoint_disable (STB_LOCAL)
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
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff817d48a0-ffffffff817d4a1f: ehci_endpoint_disable (STB_LOCAL)
ffffffff817dbcfc-ffffffff817dbd37: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff81811340-ffffffff818114bf: ehci_endpoint_disable (STB_LOCAL)
ffffffff8181879c-ffffffff818187d7: ehci_endpoint_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ehci_endpoint_disable(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:944
Inline: False
```
**Symbols:**

```
ffffffff8182be10-ffffffff8182bf8f: ehci_endpoint_disable (STB_LOCAL)
ffffffff8183278c-ffffffff818327c7: ehci_endpoint_disable.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
