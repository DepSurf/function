# Function: <code>dwc2_hc_start_transfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816230a0)
Location: drivers/usb/dwc2/core.c:1702
Inline: False
```
**Symbols:**

```
ffffffff816230a0-ffffffff81623443: dwc2_hc_start_transfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81688640)
Location: drivers/usb/dwc2/hcd.c:1339
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81688640-ffffffff81688a3f: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b6860)
Location: drivers/usb/dwc2/hcd.c:1369
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff816b6860-ffffffff816b6c5a: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816cabc0)
Location: drivers/usb/dwc2/hcd.c:1386
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff816cabc0-ffffffff816cafd6: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81737110)
Location: drivers/usb/dwc2/hcd.c:1392
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81737110-ffffffff81737535: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817770f0)
Location: drivers/usb/dwc2/hcd.c:1427
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff817770f0-ffffffff817774fd: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179cdc0)
Location: drivers/usb/dwc2/hcd.c:1417
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff8179cdc0-ffffffff8179d292: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff817db990-ffffffff817dbe7d: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff817dec20-ffffffff817dec45: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff8180c8b0-ffffffff8180cd9d: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff8180fb4b-ffffffff8180fb70: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff818dd680-ffffffff818ddb6c: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff818e0836-ffffffff818e085b: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff818e74d0-ffffffff818e79dc: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff81c1f8ad-ffffffff81c1f8d2: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1225
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff818c93b0-ffffffff818c98a6: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff81c1156f-ffffffff81c11594: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1225
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81962050-ffffffff81962651: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff81d1b664-ffffffff81d1b7e8: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1221
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81abc500-ffffffff81abcae5: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff81ee69a8-ffffffff81ee6b4b: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1192
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81c45b50-ffffffff81c4615f: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff820a21d6-ffffffff820a2352: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1192
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81cad120-ffffffff81cad72c: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff8212379c-ffffffff82123918: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1192
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81d61dd0-ffffffff81d623dc: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff82204f73-ffffffff822050ef: dwc2_hc_start_transfer.cold (STB_LOCAL)
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
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a45150)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffff800010a45150-ffff800010a4564c: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b178c8)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
c0b178c8-c0b17e40: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b08880)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
c000000000b08880-c000000000b0900c: dwc2_hc_start_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe000661a52)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffe000661a52-ffffffe000662056: dwc2_hc_start_transfer (STB_LOCAL)
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
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff817c4c90-ffffffff817c517d: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff817c7f2b-ffffffff817c7f50: dwc2_hc_start_transfer.cold (STB_LOCAL)
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
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff81801730-ffffffff81801c1d: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff818049cb-ffffffff818049f0: dwc2_hc_start_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_start_transfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1227
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
```
**Symbols:**

```
ffffffff8181b840-ffffffff8181bd2d: dwc2_hc_start_transfer (STB_LOCAL)
ffffffff8181eadb-ffffffff8181eb00: dwc2_hc_start_transfer.cold (STB_LOCAL)
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
