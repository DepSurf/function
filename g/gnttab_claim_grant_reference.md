# Function: <code>gnttab_claim_grant_reference</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c4c80)
Location: drivers/xen/grant-table.c:505
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff814c4c80-ffffffff814c4cb6: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81515400)
Location: drivers/xen/grant-table.c:504
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81515400-ffffffff81515436: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81541890)
Location: drivers/xen/grant-table.c:504
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81541890-ffffffff815418c6: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815556e0)
Location: drivers/xen/grant-table.c:505
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815556e0-ffffffff81555716: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b9320)
Location: drivers/xen/grant-table.c:590
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815b9320-ffffffff815b9356: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f16f0)
Location: drivers/xen/grant-table.c:590
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815f16f0-ffffffff815f1726: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160c330)
Location: drivers/xen/grant-table.c:594
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8160c330-ffffffff8160c366: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81640260)
Location: drivers/xen/grant-table.c:594
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81640260-ffffffff81640296: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81662820)
Location: drivers/xen/grant-table.c:594
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81662820-ffffffff81662856: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81711c40)
Location: drivers/xen/grant-table.c:593
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81711c40-ffffffff81711c76: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172e9f0)
Location: drivers/xen/grant-table.c:593
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8172e9f0-ffffffff8172ea26: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817126b0)
Location: drivers/xen/grant-table.c:593
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff817126b0-ffffffff817126e6: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8178f150)
Location: drivers/xen/grant-table.c:600
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8178f150-ffffffff8178f186: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c72d0)
Location: drivers/xen/grant-table.c:669
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff818c72d0-ffffffff818c731e: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a17c00)
Location: drivers/xen/grant-table.c:669
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a17c00-ffffffff81a17c4e: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a60c90)
Location: drivers/xen/grant-table.c:687
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a60c90-ffffffff81a60cde: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab3460)
Location: drivers/xen/grant-table.c:685
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81ab3460-ffffffff81ab34ae: gnttab_claim_grant_reference (STB_GLOBAL)
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
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082bcc8)
Location: drivers/xen/grant-table.c:594
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffff80001082bcc8-ffff80001082bd24: gnttab_claim_grant_reference (STB_GLOBAL)
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
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628690)
Location: drivers/xen/grant-table.c:594
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81628690-ffffffff816286c6: gnttab_claim_grant_reference (STB_GLOBAL)
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
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656660)
Location: drivers/xen/grant-table.c:594
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81656660-ffffffff81656696: gnttab_claim_grant_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gnttab_claim_grant_reference(grant_ref_t *private_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81670c40)
Location: drivers/xen/grant-table.c:594
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/net/xen-netfront.c:xennet_tx_setup_grant
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81670c40-ffffffff81670c76: gnttab_claim_grant_reference (STB_GLOBAL)
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
