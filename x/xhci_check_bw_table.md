# Function: <code>xhci_check_bw_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164ee93)
Location: drivers/usb/host/xhci.c:2183
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816af7f1)
Location: drivers/usb/host/xhci.c:2161
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
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
In drivers/usb/host/xhci.c (ffffffff816dd991)
Location: drivers/usb/host/xhci.c:2150
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
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
In drivers/usb/host/xhci.c (ffffffff816f198b)
Location: drivers/usb/host/xhci.c:2094
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
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
In drivers/usb/host/xhci.c (ffffffff8175dc0b)
Location: drivers/usb/host/xhci.c:2105
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
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
In drivers/usb/host/xhci.c (ffffffff8179e611)
Location: drivers/usb/host/xhci.c:2231
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
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
In drivers/usb/host/xhci.c (ffffffff817c47fc)
Location: drivers/usb/host/xhci.c:2248
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81803fa7)
Location: drivers/usb/host/xhci.c:2277
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81834e77)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2289
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff819049a0-ffffffff81904c8f: xhci_check_bw_table (STB_LOCAL)
ffffffff8190b10e-ffffffff8190b154: xhci_check_bw_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2422
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff8190d230-ffffffff8190d51f: xhci_check_bw_table (STB_LOCAL)
ffffffff81c20b3b-ffffffff81c20b81: xhci_check_bw_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2417
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff818f07c0-ffffffff818f0aaf: xhci_check_bw_table (STB_LOCAL)
ffffffff81c12b70-ffffffff81c12bb6: xhci_check_bw_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2429
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff8198d010-ffffffff8198d42f: xhci_check_bw_table (STB_LOCAL)
ffffffff81d1f81c-ffffffff81d1f862: xhci_check_bw_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2467
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81ae9250-ffffffff81ae9669: xhci_check_bw_table (STB_LOCAL)
ffffffff81eeb401-ffffffff81eeb45d: xhci_check_bw_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c75550)
Location: drivers/usb/host/xhci.c:2465
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81c75550-ffffffff81c75a1b: xhci_check_bw_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdc450)
Location: drivers/usb/host/xhci.c:2305
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81cdc450-ffffffff81cdc91b: xhci_check_bw_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_check_bw_table(struct xhci_hcd *xhci, struct xhci_virt_device *virt_dev, int old_active_eps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d91470)
Location: drivers/usb/host/xhci.c:2341
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81d91470-ffffffff81d9193b: xhci_check_bw_table (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a727f8)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b4649c)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b48074)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068ae96)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817ed227)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b2337)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81829cf7)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81843c97)
Location: drivers/usb/host/xhci.c:2286
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
