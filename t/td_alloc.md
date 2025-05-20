# Function: <code>td_alloc</code>

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
In drivers/usb/host/ohci-hcd.c (ffffffff81640280)
Location: drivers/usb/host/ohci-mem.c:86
Inline: True
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81640280-ffffffff816402f9: td_alloc.isra.33 (STB_LOCAL)
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
In drivers/usb/host/ohci-hcd.c (ffffffff816a0e60)
Location: drivers/usb/host/ohci-mem.c:86
Inline: True
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff816a0e60-ffffffff816a0ed9: td_alloc.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816cf563)
Location: drivers/usb/host/ohci-mem.c:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816e39ec)
Location: drivers/usb/host/ohci-mem.c:86
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8175020c)
Location: drivers/usb/host/ohci-mem.c:87
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8178fed9)
Location: drivers/usb/host/ohci-mem.c:87
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817b66a7)
Location: drivers/usb/host/ohci-mem.c:83
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817f4f10)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff817f4f10-ffffffff817f4f89: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81825d70)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81825d70-ffffffff81825de9: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818f7430)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff818f7430-ffffffff818f74a9: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818fff80)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff818fff80-ffffffff818ffff9: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818e3500)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff818e3500-ffffffff818e3579: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8197f7b0)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff8197f7b0-ffffffff8197f829: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81adb5a0)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff81adb5a0-ffffffff81adb62d: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c66820)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff81c66820-ffffffff81c668ad: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81ccda90)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff81ccda90-ffffffff81ccdb1d: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81d82990)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
```
**Symbols:**

```
ffffffff81d82990-ffffffff81d82a1d: td_alloc (STB_LOCAL)
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
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffff800010a5ffb0)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffff800010a5ffb0-ffff800010a60044: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c0b32418)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
c0b32418-c0b324ac: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c000000000b2e2a0)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
c000000000b2e2a0-c000000000b2e354: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffe00067b106)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffe00067b106-ffffffe00067b166: td_alloc (STB_LOCAL)
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
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817de150)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff817de150-ffffffff817de1c9: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8181abf0)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff8181abf0-ffffffff8181ac69: td_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct td *td_alloc(struct ohci_hcd *hc, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81834d40)
Location: drivers/usb/host/ohci-mem.c:90
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81834d40-ffffffff81834db9: td_alloc (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
