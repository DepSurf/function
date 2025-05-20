# Function: <code>xhci_get_ss_bw_consumed</code>

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
In drivers/usb/host/xhci.c (ffffffff8164b41b)
Location: drivers/usb/host/xhci.c:2372
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
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
In drivers/usb/host/xhci.c (ffffffff816af487)
Location: drivers/usb/host/xhci.c:2350
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
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
In drivers/usb/host/xhci.c (ffffffff816dd627)
Location: drivers/usb/host/xhci.c:2339
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
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
In drivers/usb/host/xhci.c (ffffffff816ee26f)
Location: drivers/usb/host/xhci.c:2283
Inline: True
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
In drivers/usb/host/xhci.c (ffffffff8175aa9f)
Location: drivers/usb/host/xhci.c:2294
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179a430)
Location: drivers/usb/host/xhci.c:2420
Inline: False
```
**Symbols:**

```
ffffffff8179a430-ffffffff8179a471: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c07c0)
Location: drivers/usb/host/xhci.c:2437
Inline: False
```
**Symbols:**

```
ffffffff817c07c0-ffffffff817c0801: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81800220)
Location: drivers/usb/host/xhci.c:2466
Inline: False
```
**Symbols:**

```
ffffffff81800220-ffffffff8180025f: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81830fb0)
Location: drivers/usb/host/xhci.c:2475
Inline: False
```
**Symbols:**

```
ffffffff81830fb0-ffffffff81830fef: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff819047e0)
Location: drivers/usb/host/xhci.c:2478
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff819047e0-ffffffff81904818: xhci_get_ss_bw_consumed.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190d070)
Location: drivers/usb/host/xhci.c:2611
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff8190d070-ffffffff8190d0a8: xhci_get_ss_bw_consumed.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f0600)
Location: drivers/usb/host/xhci.c:2606
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff818f0600-ffffffff818f063c: xhci_get_ss_bw_consumed.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2618
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff8198ba50-ffffffff8198bab8: xhci_get_ss_bw_consumed (STB_LOCAL)
ffffffff81d1f6a2-ffffffff81d1f6fc: xhci_get_ss_bw_consumed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2656
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff81ae7be0-ffffffff81ae7c60: xhci_get_ss_bw_consumed (STB_LOCAL)
ffffffff81eeb17a-ffffffff81eeb1d4: xhci_get_ss_bw_consumed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2654
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff81c73b60-ffffffff81c73be0: xhci_get_ss_bw_consumed (STB_LOCAL)
ffffffff820a560f-ffffffff820a5669: xhci_get_ss_bw_consumed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2494
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff81cdb0f0-ffffffff81cdb170: xhci_get_ss_bw_consumed (STB_LOCAL)
ffffffff82126b15-ffffffff82126b6a: xhci_get_ss_bw_consumed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2530
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffff81d90120-ffffffff81d901a0: xhci_get_ss_bw_consumed (STB_LOCAL)
ffffffff82208318-ffffffff8220836d: xhci_get_ss_bw_consumed.cold (STB_LOCAL)
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6d450)
Location: drivers/usb/host/xhci.c:2475
Inline: False
```
**Symbols:**

```
ffff800010a6d450-ffff800010a6d4bc: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b41778)
Location: drivers/usb/host/xhci.c:2475
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
c0b41778-c0b417d0: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b40df0)
Location: drivers/usb/host/xhci.c:2475
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
c000000000b40df0-c000000000b40e54: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068654a)
Location: drivers/usb/host/xhci.c:2475
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_add_ep_to_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
  - drivers/usb/host/xhci.c:xhci_drop_ep_from_interval_table
```
**Symbols:**

```
ffffffe00068654a-ffffffe0006865aa: xhci_get_ss_bw_consumed (STB_LOCAL)
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
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817e9390)
Location: drivers/usb/host/xhci.c:2475
Inline: False
```
**Symbols:**

```
ffffffff817e9390-ffffffff817e93cf: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817ae4a0)
Location: drivers/usb/host/xhci.c:2475
Inline: False
```
**Symbols:**

```
ffffffff817ae4a0-ffffffff817ae4df: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81825e30)
Location: drivers/usb/host/xhci.c:2475
Inline: False
```
**Symbols:**

```
ffffffff81825e30-ffffffff81825e6f: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int xhci_get_ss_bw_consumed(struct xhci_bw_info *ep_bw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8183fd10)
Location: drivers/usb/host/xhci.c:2475
Inline: False
```
**Symbols:**

```
ffffffff8183fd10-ffffffff8183fd4f: xhci_get_ss_bw_consumed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
