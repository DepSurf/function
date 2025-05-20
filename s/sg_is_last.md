# Function: <code>sg_is_last</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dee86)
Location: include/linux/scatterlist.h:89
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
```
```
In drivers/base/devcoredump.c (ffffffff819b3dbf)
Location: include/linux/scatterlist.h:89
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In net/core/skbuff.c (ffffffff81bf417a)
Location: include/linux/scatterlist.h:89
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81c8bfae)
Location: include/linux/scatterlist.h:89
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81d7b295)
Location: include/linux/scatterlist.h:89
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In lib/scatterlist.c (ffffffff817cf046)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
```
```
In drivers/base/devcoredump.c (ffffffff81b28adf)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In net/core/skbuff.c (ffffffff81da1f8a)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81e47139)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81f48305)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In lib/scatterlist.c (ffffffff8180d4f6)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
```
```
In drivers/base/devcoredump.c (ffffffff81b78c8f)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In net/core/skbuff.c (ffffffff81e107ed)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81ea2bcc)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81fa7e51)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In lib/scatterlist.c (ffffffff818531a6)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_page_iter_dma_next
  - lib/scatterlist.c:__sg_page_iter_next
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_last
  - lib/scatterlist.c:sg_nents
```
```
In drivers/base/devcoredump.c (ffffffff81bccb5f)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In net/core/skbuff.c (ffffffff81ecd30d)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
```
In net/core/skmsg.c (ffffffff81f64efc)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff82075111)
Location: include/linux/scatterlist.h:92
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
