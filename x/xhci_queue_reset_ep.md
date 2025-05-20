# Function: <code>xhci_queue_reset_ep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8165add0)
Location: drivers/usb/host/xhci-ring.c:4172
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff8165add0-ffffffff8165ae0a: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816bb660)
Location: drivers/usb/host/xhci-ring.c:4071
Inline: False
```
**Symbols:**

```
ffffffff816bb660-ffffffff816bb69e: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e9970)
Location: drivers/usb/host/xhci-ring.c:3971
Inline: False
```
**Symbols:**

```
ffffffff816e9970-ffffffff816e99ae: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fddf0)
Location: drivers/usb/host/xhci-ring.c:4068
Inline: False
```
**Symbols:**

```
ffffffff816fddf0-ffffffff816fde30: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8176a970)
Location: drivers/usb/host/xhci-ring.c:4072
Inline: False
```
**Symbols:**

```
ffffffff8176a970-ffffffff8176a9b0: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817abcc0)
Location: drivers/usb/host/xhci-ring.c:3991
Inline: False
```
**Symbols:**

```
ffffffff817abcc0-ffffffff817abd00: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d1d20)
Location: drivers/usb/host/xhci-ring.c:4055
Inline: False
```
**Symbols:**

```
ffffffff817d1d20-ffffffff817d1d60: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818115e0)
Location: drivers/usb/host/xhci-ring.c:4121
Inline: False
```
**Symbols:**

```
ffffffff818115e0-ffffffff81811620: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818427e0)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
ffffffff818427e0-ffffffff81842820: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff819119cc)
Location: drivers/usb/host/xhci-ring.c:4196
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
```
**Symbols:**

```
ffffffff819169a0-ffffffff819169e0: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff819193dc)
Location: drivers/usb/host/xhci-ring.c:4225
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
```
**Symbols:**

```
ffffffff8191df30-ffffffff8191df70: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fcf9d)
Location: drivers/usb/host/xhci-ring.c:4354
Inline: True
```
**Symbols:**

```
ffffffff81901600-ffffffff81901640: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199c0a3)
Location: drivers/usb/host/xhci-ring.c:4424
Inline: True
```
**Symbols:**

```
ffffffff819a0ed0-ffffffff819a0f10: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81af8791)
Location: drivers/usb/host/xhci-ring.c:4359
Inline: True
```
**Symbols:**

```
ffffffff81afe720-ffffffff81afe772: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8670b)
Location: drivers/usb/host/xhci-ring.c:4366
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
```
**Symbols:**

```
ffffffff81c8d550-ffffffff81c8d5a2: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ced53b)
Location: drivers/usb/host/xhci-ring.c:4384
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
```
**Symbols:**

```
ffffffff81cf40c0-ffffffff81cf4112: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da32fb)
Location: drivers/usb/host/xhci-ring.c:4427
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
```
**Symbols:**

```
ffffffff81da9a00-ffffffff81da9a52: xhci_queue_reset_ep (STB_GLOBAL)
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
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a81770)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
ffff800010a81770-ffff800010a817f0: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b54cb0)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
c0b54cb0-c0b54d08: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5ab40)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
c000000000b5ab40-c000000000b5ab8c: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000697e0e)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
ffffffe000697e0e-ffffffe000697e86: xhci_queue_reset_ep (STB_GLOBAL)
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
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817fab90)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
ffffffff817fab90-ffffffff817fabd0: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bfd30)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
ffffffff817bfd30-ffffffff817bfd70: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81837660)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
ffffffff81837660-ffffffff818376a0: xhci_queue_reset_ep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_queue_reset_ep(struct xhci_hcd *xhci, struct xhci_command *cmd, int slot_id, unsigned int ep_index, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81851a90)
Location: drivers/usb/host/xhci-ring.c:4150
Inline: False
```
**Symbols:**

```
ffffffff81851a90-ffffffff81851ad0: xhci_queue_reset_ep (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum xhci_ep_reset_type reset_type</code>
</li>
</ul>
</details>
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
