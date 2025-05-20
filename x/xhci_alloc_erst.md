# Function: <code>xhci_alloc_erst</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81764f70)
Location: drivers/usb/host/xhci-mem.c:1767
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff81764f70-ffffffff817650a4: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a52b0)
Location: drivers/usb/host/xhci-mem.c:1791
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817a52b0-ffffffff817a5406: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cb590)
Location: drivers/usb/host/xhci-mem.c:1791
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817cb590-ffffffff817cb61e: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b950)
Location: drivers/usb/host/xhci-mem.c:1791
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8180b950-ffffffff8180b9df: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c910)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8183c910-ffffffff8183c99f: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190f360)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8190f360-ffffffff8190f3ec: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916ec0)
Location: drivers/usb/host/xhci-mem.c:1805
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81916ec0-ffffffff81916f4c: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818fa340)
Location: drivers/usb/host/xhci-mem.c:1792
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff818fa340-ffffffff818fa3c9: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819990c0)
Location: drivers/usb/host/xhci-mem.c:1792
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff819990c0-ffffffff81999149: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af60b0)
Location: drivers/usb/host/xhci-mem.c:1783
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81af60b0-ffffffff81af615f: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c83a20)
Location: drivers/usb/host/xhci-mem.c:1792
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81c83a20-ffffffff81c83acf: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81cea740)
Location: drivers/usb/host/xhci-mem.c:1772
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81cea740-ffffffff81cea7ef: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d21e)
Location: drivers/usb/host/xhci-mem.c:1782
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter
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
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a7a790)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffff800010a7a790-ffff800010a7a84c: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4e090)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
c0b4e090-c0b4e148: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b52220)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
c000000000b52220-c000000000b52304: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691dda)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffe000691dda-ffffffe000691e6e: xhci_alloc_erst (STB_GLOBAL)
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
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4cc0)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff817f4cc0-ffffffff817f4d4f: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9e60)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff817b9e60-ffffffff817b9eef: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81831790)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81831790-ffffffff8183181f: xhci_alloc_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_alloc_erst(struct xhci_hcd *xhci, struct xhci_ring *evt_ring, struct xhci_erst *erst, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b970)
Location: drivers/usb/host/xhci-mem.c:1797
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8184b970-ffffffff8184b9ff: xhci_alloc_erst (STB_GLOBAL)
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
