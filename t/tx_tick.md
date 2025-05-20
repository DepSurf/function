# Function: <code>tx_tick</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff816eb3e0)
Location: drivers/mailbox/mailbox.c:94
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff816eb3e0-ffffffff816eb45a: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8174fed0)
Location: drivers/mailbox/mailbox.c:94
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff8174fed0-ffffffff8174ff4a: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8177ba90)
Location: drivers/mailbox/mailbox.c:93
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff8177ba90-ffffffff8177bb0a: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8179a6f0)
Location: drivers/mailbox/mailbox.c:93
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff8179a6f0-ffffffff8179a779: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81810ab0)
Location: drivers/mailbox/mailbox.c:93
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81810ab0-ffffffff81810b3c: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8185a950)
Location: drivers/mailbox/mailbox.c:93
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff8185a950-ffffffff8185a9dc: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81879d00)
Location: drivers/mailbox/mailbox.c:93
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81879d00-ffffffff81879d8c: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818bf2c0)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff818bf2c0-ffffffff818bf34c: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818f1e10)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff818f1e10-ffffffff818f1e9c: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819c74d0)
Location: drivers/mailbox/mailbox.c:90
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff819c74d0-ffffffff819c755c: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819c7420)
Location: drivers/mailbox/mailbox.c:93
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff819c7420-ffffffff819c74ac: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819ac360)
Location: drivers/mailbox/mailbox.c:93
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff819ac360-ffffffff819ac3ec: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:93
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff81a5a8a0-ffffffff81a5a93b: tx_tick (STB_LOCAL)
ffffffff81d314ae-ffffffff81d314c3: tx_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:93
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff81bca030-ffffffff81bca0e3: tx_tick (STB_LOCAL)
ffffffff81efd907-ffffffff81efd91c: tx_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:93
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff81d735d0-ffffffff81d73683: tx_tick (STB_LOCAL)
ffffffff820aa1ba-ffffffff820aa1cf: tx_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:93
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff81de13a0-ffffffff81de1453: tx_tick (STB_LOCAL)
ffffffff8212b6b9-ffffffff8212b6ce: tx_tick.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:94
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff81e97360-ffffffff81e97413: tx_tick (STB_LOCAL)
ffffffff8220d2cb-ffffffff8220d2e0: tx_tick.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffff800010b7a2a8)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffff800010b7a2a8-ffff800010b7a3a8: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c0c5f91c)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
c0c5f91c-c0c5f9ac: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c000000000c58fc0)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
c000000000c58fc0-c000000000c590bc: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffe00072bd38)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffe00072bd38-ffffffe00072bdce: tx_tick (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81893140)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff81893140-ffffffff818931cc: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8184b640)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff8184b640-ffffffff8184b6cc: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818e6c40)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff818e6c40-ffffffff818e6ccc: tx_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tx_tick(struct mbox_chan *chan, int r);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819038c0)
Location: drivers/mailbox/mailbox.c:90
Inline: True
Direct callers:
  - drivers/mailbox/mailbox.c:mbox_flush
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
**Symbols:**

```
ffffffff819038c0-ffffffff8190394c: tx_tick (STB_LOCAL)
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
