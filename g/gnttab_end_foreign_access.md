# Function: <code>gnttab_end_foreign_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c5a60)
Location: drivers/xen/grant-table.c:381
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff814c5a60-ffffffff814c5bc9: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81515fc0)
Location: drivers/xen/grant-table.c:380
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffffffff81515fc0-ffffffff8151613a: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81542440)
Location: drivers/xen/grant-table.c:380
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffffffff81542440-ffffffff815425b9: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815562b0)
Location: drivers/xen/grant-table.c:381
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff815562b0-ffffffff81556436: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b9db0)
Location: drivers/xen/grant-table.c:435
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff815b9db0-ffffffff815b9f36: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:435
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff815f338f-ffffffff815f33c3: gnttab_end_foreign_access.cold.27 (STB_LOCAL)
ffffffff815f1bd0-ffffffff815f1da2: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160ca77)
Location: drivers/xen/grant-table.c:439
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff8160e3ef-ffffffff8160e423: gnttab_end_foreign_access.cold.28 (STB_LOCAL)
ffffffff8160c970-ffffffff8160cb42: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81640621)
Location: drivers/xen/grant-table.c:439
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffffffff81642100-ffffffff81642134: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff81640510-ffffffff816406e9: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81662d31)
Location: drivers/xen/grant-table.c:439
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffffffff816646c0-ffffffff816646f4: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff81662c20-ffffffff81662df9: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:438
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:purge_persistent_grants
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
**Symbols:**

```
ffffffff81713ce7-ffffffff81713d48: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff817129b0-ffffffff81712a6e: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:438
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:purge_persistent_grants
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
**Symbols:**

```
ffffffff81c04af3-ffffffff81c04b54: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff8172f740-ffffffff8172f7fb: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:438
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81bf66b8-ffffffff81bf67e7: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff817137a0-ffffffff81713860: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81791010)
Location: drivers/xen/grant-table.c:446
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81791010-ffffffff8179111c: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c9680)
Location: drivers/xen/grant-table.c:587
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_teardown_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff818c9680-ffffffff818c976f: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a1a7e0)
Location: drivers/xen/grant-table.c:587
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_teardown_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81a1a7e0-ffffffff81a1a8cf: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a63990)
Location: drivers/xen/grant-table.c:605
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_teardown_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81a63990-ffffffff81a63a7f: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab61d0)
Location: drivers/xen/grant-table.c:603
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_teardown_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81ab61d0-ffffffff81ab62bc: gnttab_end_foreign_access (STB_GLOBAL)
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
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082d930)
Location: drivers/xen/grant-table.c:439
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffff80001082d930-ffff80001082db74: gnttab_end_foreign_access (STB_GLOBAL)
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
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628ba1)
Location: drivers/xen/grant-table.c:439
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffffffff8162a530-ffffffff8162a564: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff81628a90-ffffffff81628c69: gnttab_end_foreign_access (STB_GLOBAL)
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
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656b71)
Location: drivers/xen/grant-table.c:439
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffffffff81658500-ffffffff81658534: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff81656a60-ffffffff81656c39: gnttab_end_foreign_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_end_foreign_access(grant_ref_t ref, int readonly, long unsigned int page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81671151)
Location: drivers/xen/grant-table.c:439
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/block/xen-blkfront.c:blkif_free_ring
```
**Symbols:**

```
ffffffff81672b00-ffffffff81672b34: gnttab_end_foreign_access.cold (STB_LOCAL)
ffffffff81671040-ffffffff81671219: gnttab_end_foreign_access (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int readonly</code>
</li>
<li>
<b>Param reordered. </b>
<code>ref, readonly, page</code> ➡️ <code>ref, page</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int page</code> ➡️ <code>struct page *page</code>
</li>
</ul>
</details>
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
