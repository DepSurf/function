# Function: <code>dwc2_queue_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81627a50)
Location: drivers/usb/dwc2/hcd.c:1002
Inline: True
```
**Symbols:**

```
ffffffff81627a50-ffffffff81627b51: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81688b50)
Location: drivers/usb/dwc2/hcd.c:2839
Inline: False
```
**Symbols:**

```
ffffffff81688b50-ffffffff81688c93: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b6d70)
Location: drivers/usb/dwc2/hcd.c:2870
Inline: False
```
**Symbols:**

```
ffffffff816b6d70-ffffffff816b6eb1: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816cb0e0)
Location: drivers/usb/dwc2/hcd.c:2883
Inline: False
```
**Symbols:**

```
ffffffff816cb0e0-ffffffff816cb213: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81737640)
Location: drivers/usb/dwc2/hcd.c:2889
Inline: False
```
**Symbols:**

```
ffffffff81737640-ffffffff81737779: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81777610)
Location: drivers/usb/dwc2/hcd.c:3006
Inline: False
```
**Symbols:**

```
ffffffff81777610-ffffffff81777749: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179d3d0)
Location: drivers/usb/dwc2/hcd.c:2996
Inline: False
```
**Symbols:**

```
ffffffff8179d3d0-ffffffff8179d509: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817dbfb0)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
ffffffff817dbfb0-ffffffff817dc107: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8180ced0)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
ffffffff8180ced0-ffffffff8180d027: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818ddca0)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff818ddca0-ffffffff818dde11: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e7b10)
Location: drivers/usb/dwc2/hcd.c:2817
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff818e7b10-ffffffff818e7c81: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c99e0)
Location: drivers/usb/dwc2/hcd.c:2815
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff818c99e0-ffffffff818c9b51: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2815
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff819627d0-ffffffff8196296e: dwc2_queue_transaction (STB_LOCAL)
ffffffff81d1b82d-ffffffff81d1b85b: dwc2_queue_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2811
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff81abcc70-ffffffff81abcdf1: dwc2_queue_transaction (STB_LOCAL)
ffffffff81ee6b90-ffffffff81ee6bc0: dwc2_queue_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2782
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff81c46300-ffffffff81c46481: dwc2_queue_transaction (STB_LOCAL)
ffffffff820a2397-ffffffff820a23c7: dwc2_queue_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2782
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff81cad8d0-ffffffff81cada50: dwc2_queue_transaction (STB_LOCAL)
ffffffff8212395d-ffffffff8212398d: dwc2_queue_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2782
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_non_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
```
**Symbols:**

```
ffffffff81d62580-ffffffff81d62700: dwc2_queue_transaction (STB_LOCAL)
ffffffff82205134-ffffffff82205164: dwc2_queue_transaction.cold (STB_LOCAL)
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
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a457b8)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
ffff800010a457b8-ffff800010a45928: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b17fe8)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
c0b17fe8-c0b18160: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b09310)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
c000000000b09310-c000000000b0957c: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe000662220)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
ffffffe000662220-ffffffe00066234e: dwc2_queue_transaction (STB_LOCAL)
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
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c52b0)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
ffffffff817c52b0-ffffffff817c5407: dwc2_queue_transaction (STB_LOCAL)
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
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81801d50)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
ffffffff81801d50-ffffffff81801ea7: dwc2_queue_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dwc2_queue_transaction(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, u16 fifo_dwords_avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181be60)
Location: drivers/usb/dwc2/hcd.c:2816
Inline: False
```
**Symbols:**

```
ffffffff8181be60-ffffffff8181bfb7: dwc2_queue_transaction (STB_LOCAL)
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
