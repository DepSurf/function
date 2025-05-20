# Function: <code>gnttab_grant_foreign_access_ref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c48d0)
Location: drivers/xen/grant-table.c:235
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff814c48d0-ffffffff814c48f3: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815158fc)
Location: drivers/xen/grant-table.c:234
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81515050-ffffffff81515073: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81541d8c)
Location: drivers/xen/grant-table.c:234
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815414e0-ffffffff81541503: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81555bcc)
Location: drivers/xen/grant-table.c:235
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81555330-ffffffff81555353: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b981c)
Location: drivers/xen/grant-table.c:261
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815b8ef0-ffffffff815b8f19: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f31c2)
Location: drivers/xen/grant-table.c:261
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815f1520-ffffffff815f1549: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160d792)
Location: drivers/xen/grant-table.c:265
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8160c160-ffffffff8160c189: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816411c0)
Location: drivers/xen/grant-table.c:265
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8163fdf0-ffffffff8163fe19: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81663b80)
Location: drivers/xen/grant-table.c:265
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff816623b0-ffffffff816623d9: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81712d80)
Location: drivers/xen/grant-table.c:264
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
  - drivers/block/xen-blkfront.c:get_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff817118c0-ffffffff817118e9: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172fb80)
Location: drivers/xen/grant-table.c:264
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
  - drivers/block/xen-blkfront.c:get_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8172e5e0-ffffffff8172e609: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81713690)
Location: drivers/xen/grant-table.c:264
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff817122a0-ffffffff817122c9: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817902e0)
Location: drivers/xen/grant-table.c:261
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8178ed10-ffffffff8178ed39: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c862d)
Location: drivers/xen/grant-table.c:405
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff818c6d50-ffffffff818c6d87: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a1903d)
Location: drivers/xen/grant-table.c:405
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a17750-ffffffff81a17787: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a620ad)
Location: drivers/xen/grant-table.c:405
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a607e0-ffffffff81a60817: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab48dd)
Location: drivers/xen/grant-table.c:405
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81ab3020-ffffffff81ab3057: gnttab_grant_foreign_access_ref (STB_GLOBAL)
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
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082df04)
Location: drivers/xen/grant-table.c:265
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffff80001082b9a0-ffff80001082ba00: gnttab_grant_foreign_access_ref (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816299f0)
Location: drivers/xen/grant-table.c:265
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81628220-ffffffff81628249: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816579c0)
Location: drivers/xen/grant-table.c:265
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff816561f0-ffffffff81656219: gnttab_grant_foreign_access_ref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void gnttab_grant_foreign_access_ref(grant_ref_t ref, domid_t domid, long unsigned int frame, int readonly);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81671fc0)
Location: drivers/xen/grant-table.c:265
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_grant_foreign_access
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff816707d0-ffffffff816707f9: gnttab_grant_foreign_access_ref (STB_GLOBAL)
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
