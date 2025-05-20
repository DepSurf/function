# Function: <code>xennet_get_responses</code>

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
In drivers/net/xen-netfront.c (ffffffff815fb451)
Location: drivers/net/xen-netfront.c:763
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8165b377)
Location: drivers/net/xen-netfront.c:754
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81689197)
Location: drivers/net/xen-netfront.c:777
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8169e8fc)
Location: drivers/net/xen-netfront.c:778
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81709a9c)
Location: drivers/net/xen-netfront.c:780
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81748591)
Location: drivers/net/xen-netfront.c:783
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8176c641)
Location: drivers/net/xen-netfront.c:782
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817aa450)
Location: drivers/net/xen-netfront.c:781
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817cdeb0)
Location: drivers/net/xen-netfront.c:781
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:783
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81899be0-ffffffff81899e4a: xennet_get_responses (STB_LOCAL)
ffffffff8189a7d1-ffffffff8189a85c: xennet_get_responses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list, bool *need_xdp_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:905
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff818a8ca0-ffffffff818a8f90: xennet_get_responses (STB_LOCAL)
ffffffff81c19e97-ffffffff81c19f2e: xennet_get_responses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list, bool *need_xdp_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:903
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff8188bda0-ffffffff8188c1f6: xennet_get_responses (STB_LOCAL)
ffffffff81c0bc98-ffffffff81c0bd92: xennet_get_responses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list, bool *need_xdp_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:977
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff8191ed30-ffffffff8191f284: xennet_get_responses (STB_LOCAL)
ffffffff81d11417-ffffffff81d1154a: xennet_get_responses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list, bool *need_xdp_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1014
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81a74050-ffffffff81a745f0: xennet_get_responses (STB_LOCAL)
ffffffff81edc181-ffffffff81edc288: xennet_get_responses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list, bool *need_xdp_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c081a0)
Location: drivers/net/xen-netfront.c:1014
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81c081a0-ffffffff81c08831: xennet_get_responses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list, bool *need_xdp_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c6d8b0)
Location: drivers/net/xen-netfront.c:1014
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81c6d8b0-ffffffff81c6df99: xennet_get_responses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xennet_get_responses(struct netfront_queue *queue, struct netfront_rx_info *rinfo, RING_IDX rp, struct sk_buff_head *list, bool *need_xdp_flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d22200)
Location: drivers/net/xen-netfront.c:1015
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81d22200-ffffffff81d2288d: xennet_get_responses (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffff800010a08740)
Location: drivers/net/xen-netfront.c:781
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/net/xen-netfront.c (ffffffff81792ad0)
Location: drivers/net/xen-netfront.c:813
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817c2d30)
Location: drivers/net/xen-netfront.c:781
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817dcff0)
Location: drivers/net/xen-netfront.c:781
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *need_xdp_flush</code>
</li>
</ul>
</details>
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
