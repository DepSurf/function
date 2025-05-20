# Function: <code>xennet_tx_buf_gc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff815fa940)
Location: drivers/net/xen-netfront.c:362
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff815fa940-ffffffff815faafd: xennet_tx_buf_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8165a800)
Location: drivers/net/xen-netfront.c:362
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff8165a800-ffffffff8165a9de: xennet_tx_buf_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81688560)
Location: drivers/net/xen-netfront.c:370
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81688560-ffffffff8168873e: xennet_tx_buf_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8169dd10)
Location: drivers/net/xen-netfront.c:371
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff8169dd10-ffffffff8169dee1: xennet_tx_buf_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81708eb0)
Location: drivers/net/xen-netfront.c:373
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81708eb0-ffffffff81709084: xennet_tx_buf_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:376
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81747a10-ffffffff81747bcf: xennet_tx_buf_gc (STB_LOCAL)
ffffffff8174a3cc-ffffffff8174a3e1: xennet_tx_buf_gc.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:374
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff8176bb00-ffffffff8176bcb9: xennet_tx_buf_gc (STB_LOCAL)
ffffffff8176e556-ffffffff8176e56b: xennet_tx_buf_gc.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:374
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff817a98f0-ffffffff817a9aa9: xennet_tx_buf_gc (STB_LOCAL)
ffffffff817ac24d-ffffffff817ac262: xennet_tx_buf_gc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:374
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff817cd360-ffffffff817cd519: xennet_tx_buf_gc (STB_LOCAL)
ffffffff817cfc8d-ffffffff817cfca2: xennet_tx_buf_gc.cold (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff8189a4e5)
Location: drivers/net/xen-netfront.c:376
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_start_xmit
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81897e10-ffffffff81897fb8: xennet_tx_buf_gc.part.0 (STB_LOCAL)
ffffffff8189a700-ffffffff8189a715: xennet_tx_buf_gc.part.0.cold (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffffffff818a84c2)
Location: drivers/net/xen-netfront.c:388
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit_one
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit_one
```
**Symbols:**

```
ffffffff818a61d0-ffffffff818a6378: xennet_tx_buf_gc.part.0 (STB_LOCAL)
ffffffff81c19d08-ffffffff81c19d1d: xennet_tx_buf_gc.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:388
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81889590-ffffffff8188974e: xennet_tx_buf_gc (STB_LOCAL)
ffffffff81c0bac8-ffffffff81c0badd: xennet_tx_buf_gc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:382
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff8191b870-ffffffff8191bbbb: xennet_tx_buf_gc (STB_LOCAL)
ffffffff81d1116c-ffffffff81d111e4: xennet_tx_buf_gc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:388
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81a709c0-ffffffff81a70d0b: xennet_tx_buf_gc (STB_LOCAL)
ffffffff81edbe49-ffffffff81edbeb4: xennet_tx_buf_gc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c06230)
Location: drivers/net/xen-netfront.c:388
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81c06230-ffffffff81c06645: xennet_tx_buf_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c6b920)
Location: drivers/net/xen-netfront.c:388
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81c6b920-ffffffff81c6bd57: xennet_tx_buf_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d202f0)
Location: drivers/net/xen-netfront.c:389
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81d202f0-ffffffff81d20708: xennet_tx_buf_gc (STB_LOCAL)
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
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffff800010a06bd8)
Location: drivers/net/xen-netfront.c:374
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffff800010a06bd8-ffff800010a06d64: xennet_tx_buf_gc (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:391
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff81791f80-ffffffff81792139: xennet_tx_buf_gc (STB_LOCAL)
ffffffff81794901-ffffffff81794916: xennet_tx_buf_gc.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:374
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff817c21e0-ffffffff817c2399: xennet_tx_buf_gc (STB_LOCAL)
ffffffff817c4b0d-ffffffff817c4b22: xennet_tx_buf_gc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xennet_tx_buf_gc(struct netfront_queue *queue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:374
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff817dc4a0-ffffffff817dc659: xennet_tx_buf_gc (STB_LOCAL)
ffffffff817dedb4-ffffffff817dedc9: xennet_tx_buf_gc.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
