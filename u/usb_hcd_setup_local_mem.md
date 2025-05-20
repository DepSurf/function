# Function: <code>usb_hcd_setup_local_mem</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2918
Inline: False
```
**Symbols:**

```
ffffffff817beee5-ffffffff817bef02: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff817bbff0-ffffffff817bc095: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
ffffffff817ef865-ffffffff817ef882: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff817ec820-ffffffff817ec8c5: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2918
Inline: False
```
**Symbols:**

```
ffffffff818beec1-ffffffff818beede: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff818bbf00-ffffffff818bbfa5: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2931
Inline: False
```
**Symbols:**

```
ffffffff81c1c4ee-ffffffff81c1c50b: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff818c8cc0-ffffffff818c8d65: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2935
Inline: False
```
**Symbols:**

```
ffffffff81c0e2ca-ffffffff81c0e2e7: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff818ac270-ffffffff818ac315: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:3091
Inline: False
```
**Symbols:**

```
ffffffff81d153e2-ffffffff81d153ff: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff819412c0-ffffffff81941365: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:3118
Inline: False
```
**Symbols:**

```
ffffffff81ee00fb-ffffffff81ee0118: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff81a999f0-ffffffff81a99aa7: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1d800)
Location: drivers/usb/core/hcd.c:3112
Inline: False
```
**Symbols:**

```
ffffffff81c1d800-ffffffff81c1d93a: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c846f0)
Location: drivers/usb/core/hcd.c:3116
Inline: False
```
**Symbols:**

```
ffffffff81c846f0-ffffffff81c8482a: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d390f0)
Location: drivers/usb/core/hcd.c:3084
Inline: False
```
**Symbols:**

```
ffffffff81d390f0-ffffffff81d3922a: usb_hcd_setup_local_mem (STB_GLOBAL)
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
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1b920)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
ffff800010a1b920-ffff800010a1ba04: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af3878)
Location: drivers/usb/core/hcd.c:2921
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
```
**Symbols:**

```
c0af3878-c0af393c: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad5370)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
c000000000ad5370-c000000000ad54b4: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe00063feee)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
ffffffe00063feee-ffffffe00063ff98: usb_hcd_setup_local_mem (STB_GLOBAL)
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
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
ffffffff817a7c45-ffffffff817a7c62: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff817a4c00-ffffffff817a4ca5: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
ffffffff8179965e-ffffffff8179967b: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff81796710-ffffffff817967b5: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
ffffffff817e46e5-ffffffff817e4702: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff817e16a0-ffffffff817e1745: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_hcd_setup_local_mem(struct usb_hcd *hcd, phys_addr_t phys_addr, dma_addr_t dma, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2921
Inline: False
```
**Symbols:**

```
ffffffff817fe951-ffffffff817fe96e: usb_hcd_setup_local_mem.cold (STB_LOCAL)
ffffffff817fba90-ffffffff817fbb35: usb_hcd_setup_local_mem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
