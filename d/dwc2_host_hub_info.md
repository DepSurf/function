# Function: <code>dwc2_host_hub_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dwc2_host_hub_info(struct dwc2_hsotg *hsotg, void *context, int *hub_addr, int *hub_port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81628201)
Location: drivers/usb/dwc2/hcd.c:2154
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
**Symbols:**

```
ffffffff816298e0-ffffffff81629919: dwc2_host_hub_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dwc2_host_hub_info(struct dwc2_hsotg *hsotg, void *context, int *hub_addr, int *hub_port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81686526)
Location: drivers/usb/dwc2/hcd.c:4040
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81689660-ffffffff81689699: dwc2_host_hub_info (STB_GLOBAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff816b4763)
Location: drivers/usb/dwc2/hcd.c:669
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff816c8aec)
Location: drivers/usb/dwc2/hcd.c:686
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
In drivers/usb/dwc2/hcd.c (ffffffff81734fef)
Location: drivers/usb/dwc2/hcd.c:692
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff817754c3)
Location: drivers/usb/dwc2/hcd.c:709
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff8179aa63)
Location: drivers/usb/dwc2/hcd.c:702
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817d9c1c)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff8180aab0)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818daed9)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e4c69)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c7b31)
Location: drivers/usb/dwc2/hcd.c:510
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8195f9a9)
Location: drivers/usb/dwc2/hcd.c:510
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ab9e39)
Location: drivers/usb/dwc2/hcd.c:506
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c43229)
Location: drivers/usb/dwc2/hcd.c:477
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81caa989)
Location: drivers/usb/dwc2/hcd.c:477
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff81d5f639)
Location: drivers/usb/dwc2/hcd.c:477
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffff800010a41378)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (c0b13a5c)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (c000000000b01e58)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffe00065d2e6)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817c2e90)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817ff930)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff81819a40)
Location: drivers/usb/dwc2/hcd.c:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
</ul>
