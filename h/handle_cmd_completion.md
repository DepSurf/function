# Function: <code>handle_cmd_completion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8165a1f0)
Location: drivers/usb/host/xhci-ring.c:1289
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8165a1f0-ffffffff8165adcb: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816ba9a0)
Location: drivers/usb/host/xhci-ring.c:1313
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816ba9a0-ffffffff816bb656: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e8c10)
Location: drivers/usb/host/xhci-ring.c:1325
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816e8c10-ffffffff816e9969: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fce50)
Location: drivers/usb/host/xhci-ring.c:1370
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816fce50-ffffffff816fddec: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817699d0)
Location: drivers/usb/host/xhci-ring.c:1357
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817699d0-ffffffff8176a96f: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817aac80)
Location: drivers/usb/host/xhci-ring.c:1357
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817aac80-ffffffff817abcbb: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d0c30)
Location: drivers/usb/host/xhci-ring.c:1361
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817d0c30-ffffffff817d1d15: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81810d60-ffffffff818115d5: handle_cmd_completion (STB_LOCAL)
ffffffff8181360d-ffffffff818136c1: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81841f50-ffffffff818427e0: handle_cmd_completion (STB_LOCAL)
ffffffff8184480f-ffffffff8184488a: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1398
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81916160-ffffffff819165e8: handle_cmd_completion (STB_LOCAL)
ffffffff8191755c-ffffffff819175ac: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1403
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff8191d730-ffffffff8191dba0: handle_cmd_completion (STB_LOCAL)
ffffffff81c2246f-ffffffff81c224b7: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1641
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff818fff30-ffffffff819004b3: handle_cmd_completion (STB_LOCAL)
ffffffff81c145e6-ffffffff81c14649: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1705
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff8199f6d0-ffffffff8199fc40: handle_cmd_completion (STB_LOCAL)
ffffffff81d2175d-ffffffff81d217c0: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1639
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81afcb80-ffffffff81afd2dc: handle_cmd_completion (STB_LOCAL)
ffffffff81eed38e-ffffffff81eed41a: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8b6d0)
Location: drivers/usb/host/xhci-ring.c:1641
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81c8b6d0-ffffffff81c8bedd: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2220)
Location: drivers/usb/host/xhci-ring.c:1663
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81cf2220-ffffffff81cf2a34: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da7b90)
Location: drivers/usb/host/xhci-ring.c:1671
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81da7b90-ffffffff81da83aa: handle_cmd_completion (STB_LOCAL)
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
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a80ea0)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffff800010a80ea0-ffff800010a81770: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b541dc)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c0b541dc-c0b54cb0: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b59f40)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c000000000b59f40-c000000000b5ab34: handle_cmd_completion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000697664)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffe000697664-ffffffe000697e0e: handle_cmd_completion (STB_LOCAL)
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
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817fa300-ffffffff817fab90: handle_cmd_completion (STB_LOCAL)
ffffffff817fcbbf-ffffffff817fcc3a: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817bf4a0-ffffffff817bfd30: handle_cmd_completion (STB_LOCAL)
ffffffff817c1d5f-ffffffff817c1dda: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81836dd0-ffffffff81837660: handle_cmd_completion (STB_LOCAL)
ffffffff8183968f-ffffffff8183970a: handle_cmd_completion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void handle_cmd_completion(struct xhci_hcd *xhci, struct xhci_event_cmd *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1372
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81851160-ffffffff81851a87: handle_cmd_completion (STB_LOCAL)
ffffffff81853ae2-ffffffff81853b5d: handle_cmd_completion.cold (STB_LOCAL)
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
