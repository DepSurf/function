# Function: <code>gnttab_foreach_grant_in_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c55c0)
Location: drivers/xen/grant-table.c:779
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_make_txreqs
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff814c55c0-ffffffff814c56c1: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81516190)
Location: drivers/xen/grant-table.c:778
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff81516190-ffffffff81516293: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81542610)
Location: drivers/xen/grant-table.c:778
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff81542610-ffffffff8154270d: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815564e0)
Location: drivers/xen/grant-table.c:779
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff815564e0-ffffffff815565d3: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b9fe0)
Location: drivers/xen/grant-table.c:871
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff815b9fe0-ffffffff815ba0d6: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f1e50)
Location: drivers/xen/grant-table.c:871
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff815f1e50-ffffffff815f1f46: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160d990)
Location: drivers/xen/grant-table.c:984
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff8160d990-ffffffff8160da86: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641b40)
Location: drivers/xen/grant-table.c:984
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff81641b40-ffffffff81641c2f: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81664100)
Location: drivers/xen/grant-table.c:984
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff81664100-ffffffff816641ef: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817127e0)
Location: drivers/xen/grant-table.c:982
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
**Symbols:**

```
ffffffff817127e0-ffffffff817128cf: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172f570)
Location: drivers/xen/grant-table.c:1105
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit_one
```
**Symbols:**

```
ffffffff8172f570-ffffffff8172f65f: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81712fc0)
Location: drivers/xen/grant-table.c:1105
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81712fc0-ffffffff817130ae: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8178fa80)
Location: drivers/xen/grant-table.c:1112
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff8178fa80-ffffffff8178fb6e: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c7bc0)
Location: drivers/xen/grant-table.c:1178
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff818c7bc0-ffffffff818c7cb3: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a187b0)
Location: drivers/xen/grant-table.c:1181
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81a187b0-ffffffff81a188a3: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a61830)
Location: drivers/xen/grant-table.c:1199
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81a61830-ffffffff81a61923: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab4060)
Location: drivers/xen/grant-table.c:1197
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81ab4060-ffffffff81ab4153: gnttab_foreach_grant_in_range (STB_GLOBAL)
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
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082bc20)
Location: drivers/xen/grant-table.c:984
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffff80001082bc20-ffff80001082bcc4: gnttab_foreach_grant_in_range (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81629f70)
Location: drivers/xen/grant-table.c:984
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff81629f70-ffffffff8162a05f: gnttab_foreach_grant_in_range (STB_GLOBAL)
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
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81657f40)
Location: drivers/xen/grant-table.c:984
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff81657f40-ffffffff8165802f: gnttab_foreach_grant_in_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gnttab_foreach_grant_in_range(struct page *page, unsigned int offset, unsigned int len, xen_grant_fn_t fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81672540)
Location: drivers/xen/grant-table.c:984
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_make_txreqs
```
**Symbols:**

```
ffffffff81672540-ffffffff8167262f: gnttab_foreach_grant_in_range (STB_GLOBAL)
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
