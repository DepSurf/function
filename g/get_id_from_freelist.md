# Function: <code>get_id_from_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_info *info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81572dc0)
Location: drivers/block/xen-blkfront.c:204
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff815fa23b)
Location: drivers/net/xen-netfront.c:189
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff81572dc0-ffffffff8157303d: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815c8680)
Location: drivers/block/xen-blkfront.c:262
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8165a0fb)
Location: drivers/net/xen-netfront.c:189
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff815c8680-ffffffff815c8900: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f53d0)
Location: drivers/block/xen-blkfront.c:262
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff81687e1b)
Location: drivers/net/xen-netfront.c:189
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff815f53d0-ffffffff815f5650: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81609620)
Location: drivers/block/xen-blkfront.c:266
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8169d1db)
Location: drivers/net/xen-netfront.c:190
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff81609620-ffffffff816098a0: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81671ef0)
Location: drivers/block/xen-blkfront.c:266
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8170823b)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff81671ef0-ffffffff8167216f: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816ad9f0)
Location: drivers/block/xen-blkfront.c:266
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff81746f0b)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff816ad9f0-ffffffff816adc62: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816ce8c0)
Location: drivers/block/xen-blkfront.c:265
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8176b01b)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff816ce8c0-ffffffff816ceb32: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81709ff0)
Location: drivers/block/xen-blkfront.c:265
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817a8e1b)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff81709ff0-ffffffff8170a270: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8172e2f0)
Location: drivers/block/xen-blkfront.c:265
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817cc88b)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff8172e2f0-ffffffff8172e570: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817eaf00)
Location: drivers/block/xen-blkfront.c:276
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_discard_req
```
```
In drivers/net/xen-netfront.c (ffffffff818977fb)
Location: drivers/net/xen-netfront.c:194
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff817eaf00-ffffffff817eb180: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817ff840)
Location: drivers/block/xen-blkfront.c:276
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_discard_req
```
```
In drivers/net/xen-netfront.c (ffffffff818a556b)
Location: drivers/net/xen-netfront.c:206
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff817ff840-ffffffff817ffac0: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e4560)
Location: drivers/block/xen-blkfront.c:276
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff81888b6b)
Location: drivers/net/xen-netfront.c:206
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff817e4560-ffffffff817e47e3: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81870cb0)
Location: drivers/block/xen-blkfront.c:279
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81870cb0-ffffffff81870f33: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff819b8dc0)
Location: drivers/block/xen-blkfront.c:283
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff819b8dc0-ffffffff819b904c: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b2e1c0)
Location: drivers/block/xen-blkfront.c:286
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81b2e1c0-ffffffff81b2e44c: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b81660)
Location: drivers/block/xen-blkfront.c:286
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81b81660-ffffffff81b818ce: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd5520)
Location: drivers/block/xen-blkfront.c:286
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81bd5520-ffffffff81bd578e: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff8000109251e0)
Location: drivers/block/xen-blkfront.c:265
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffff800010a06314)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffff8000109251e0-ffff80001092542c: get_id_from_freelist (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f43c0)
Location: drivers/block/xen-blkfront.c:280
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff8179136b)
Location: drivers/net/xen-netfront.c:209
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff816f43c0-ffffffff816f4640: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817217b0)
Location: drivers/block/xen-blkfront.c:265
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817c170b)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff817217b0-ffffffff81721a30: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_id_from_freelist(struct blkfront_ring_info *rinfo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8173cb80)
Location: drivers/block/xen-blkfront.c:265
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817db9cb)
Location: drivers/net/xen-netfront.c:192
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
```
**Symbols:**

```
ffffffff8173cb80-ffffffff8173ce00: get_id_from_freelist (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blkfront_ring_info *rinfo</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blkfront_info *info</code>
</li>
</ul>
</details>
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
