# Function: <code>sg_mark_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8139eb7b)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In crypto/eseqiv.c (ffffffff813a2920)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
```
```
In block/blk-merge.c (ffffffff813bffde)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff813e7da0)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff813f9eb6)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
  - lib/scatterlist.c:__sg_alloc_table
```
```
In net/core/skbuff.c (ffffffff8170598e)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813db93d)
Location: include/linux/scatterlist.h:186
Inline: True
```
```
In block/blk-merge.c (ffffffff8140406b)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8142e036)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81440fef)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skbuff.c (ffffffff8176c65e)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813f327d)
Location: include/linux/scatterlist.h:186
Inline: True
```
```
In crypto/scompress.c (ffffffff813fac1e)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/xts.c (ffffffff81401b7b)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In block/blk-merge.c (ffffffff8141e4cc)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff81447deb)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8145e20f)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skbuff.c (ffffffff8179a09e)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813ff594)
Location: include/linux/scatterlist.h:186
Inline: True
```
```
In crypto/scompress.c (ffffffff81407636)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/xts.c (ffffffff8140ef4c)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In block/blk-merge.c (ffffffff8142bd9a)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8145679c)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81463492)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff817b9745)
Location: include/linux/scatterlist.h:186
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81427b54)
Location: include/linux/scatterlist.h:193
Inline: True
```
```
In crypto/scompress.c (ffffffff8142ff78)
Location: include/linux/scatterlist.h:193
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/xts.c (ffffffff81437a1c)
Location: include/linux/scatterlist.h:193
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In block/blk-merge.c (ffffffff8145715c)
Location: include/linux/scatterlist.h:193
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8148236c)
Location: include/linux/scatterlist.h:193
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8148f3a2)
Location: include/linux/scatterlist.h:193
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff81831f95)
Location: include/linux/scatterlist.h:193
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cf835)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
```
In crypto/scatterwalk.c (ffffffff8145a9b4)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In crypto/xts.c (ffffffff8146a32f)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
```
In block/blk-merge.c (ffffffff8148ab47)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff814b6f50)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff814c3fb2)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff8187c655)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81478524)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffff814a469a)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff814ca722)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff814d86b2)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff8189cfd5)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff818e642c)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819778d4)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814a6348)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffff814d245f)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff814f90bd)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81504506)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff818e7785)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81935da8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e13f1)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814c0fd8)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffff814eb7df)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff81516f59)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81522516)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff81919a95)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81968ac8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a187b3)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81521888)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff8154b532)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8157772d)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81585876)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836fa8)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In net/core/skbuff.c (ffffffff819ea966)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81a3bc8f)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b094ac)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b22f35)
Location: include/linux/scatterlist.h:204
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8153e6f8)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff815675e2)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff815942ba)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff815a377b)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff81847a18)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In net/core/skbuff.c (ffffffff819ea6a6)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81a3f87a)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17ccc)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b31925)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81546da8)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff8156f9cf)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8159b09c)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff815aa337)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182aa94)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In net/core/skbuff.c (ffffffff819d0c66)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81a4ea4f)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0589e)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b1f655)
Location: include/linux/scatterlist.h:203
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff815a7588)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff815d406f)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff816032fa)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff816133c4)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b651d)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In net/core/skbuff.c (ffffffff81a7fe16)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81b075b8)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc83fb)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81be4275)
Location: include/linux/scatterlist.h:209
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8164e69f)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff8167fec3)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff816b5b76)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff816df9c4)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a01a16)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In net/core/skbuff.c (ffffffff81bf4336)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81c8cd26)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dcc4)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81d7b707)
Location: include/linux/scatterlist.h:226
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81707aef)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff8173d263)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff81775e26)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff817cffc3)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b80076)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In net/core/skbuff.c (ffffffff81da2156)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81e459b7)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:alloc_sk_msg
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27974)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81f48797)
Location: include/linux/scatterlist.h:229
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8174125f)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff81779803)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff817b5ad6)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8180ee3d)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd40d8)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In net/core/skbuff.c (ffffffff81e10a26)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81ea0fc7)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/core/skmsg.c:alloc_sk_msg
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f876d6)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81fa8607)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff817820ff)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
```
```
In block/blk-merge.c (ffffffff817bbbd3)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff817fa4e6)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81854ac0)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28d48)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In net/core/skbuff.c (ffffffff81ecd546)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81f636a6)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/core/skmsg.c:alloc_sk_msg
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ed56)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff820758f7)
Location: include/linux/scatterlist.h:253
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffff8000105bafc8)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffff8000105ea1f4)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffff80001061e3a8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffff80001062c198)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In lib/sg_split.c (ffff8000106675d8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/sg_split.c:sg_split
```
```
In net/core/skbuff.c (ffff800010bb2b8c)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffff800010c0f928)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3f90)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c07692f4)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (c07967cc)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (c07c5ec0)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (c07d2b94)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In lib/sg_split.c (c080fd38)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/sg_split.c:sg_split
```
```
In net/core/skbuff.c (c0cd1098)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (c0d2626c)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (c0ddde80)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c000000000741680)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (c00000000077f08c)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (c0000000007bd5a4)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (c0000000007ceb0c)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (c000000000c8acdc)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (c000000000cfa758)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (c000000000df3434)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffe000400d16)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffe00042a604)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffe00045103c)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffe00045c3d8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skbuff.c (ffffffe000744012)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffe00078b418)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824dc4)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b95b8)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffff814e3dbf)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8150f539)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8151aaf6)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff818b9a95)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81908a98)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7e43)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814a9fd8)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffff814d469f)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff814ff957)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff8150ade6)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff818739e5)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff818c28a8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974c33)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b5648)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffff814dfe4f)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff8150b5c9)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81516b86)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff8190aa95)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81959ac8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a228c3)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814ce0e8)
Location: include/linux/scatterlist.h:190
Inline: True
```
```
In block/blk-merge.c (ffffffff814f8caf)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-integrity.c (ffffffff81524c69)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
```
```
In lib/scatterlist.c (ffffffff81530316)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skbuff.c (ffffffff8192bb95)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff8197bce8)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dc74)
Location: include/linux/scatterlist.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
</ul>

## Differences
