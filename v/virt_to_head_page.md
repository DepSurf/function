# Function: <code>virt_to_head_page</code>

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
In kernel/resource.c (ffffffff810867ba)
Location: include/linux/mm.h:500
Inline: True
```
```
In mm/page_alloc.c (ffffffff81194475)
Location: include/linux/mm.h:500
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_page_frag
```
```
In mm/list_lru.c (ffffffff811b8f8c)
Location: include/linux/mm.h:500
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_del
```
```
In mm/slub.c (ffffffff811e8a5b)
Location: include/linux/mm.h:500
Inline: True
Inline callers:
  - mm/slub.c:ksize
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
```
```
In drivers/net/virtio_net.c (ffffffff815f1450)
Location: include/linux/mm.h:500
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:free_unused_bufs
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In net/core/skbuff.c (ffffffff8170b73b)
Location: include/linux/mm.h:500
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:build_skb
  - net/core/skbuff.c:skb_gro_receive
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
In kernel/resource.c (ffffffff8108980d)
Location: include/linux/mm.h:553
Inline: True
```
```
In mm/page_alloc.c (ffffffff811a780f)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_page_frag
```
```
In mm/list_lru.c (ffffffff811d3a3f)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff8120add3)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/usercopy.c (ffffffff8122e66c)
Location: include/linux/mm.h:553
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff816523d3)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In net/core/skbuff.c (ffffffff8177338c)
Location: include/linux/mm.h:553
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb
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
In kernel/resource.c (ffffffff8108e75d)
Location: include/linux/mm.h:540
Inline: True
```
```
In mm/page_alloc.c (ffffffff811b7bff)
Location: include/linux/mm.h:540
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/list_lru.c (ffffffff811e390b)
Location: include/linux/mm.h:540
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff8121ce23)
Location: include/linux/mm.h:540
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/usercopy.c (ffffffff81240b9c)
Location: include/linux/mm.h:540
Inline: True
```
```
In net/core/skbuff.c (ffffffff817a059f)
Location: include/linux/mm.h:540
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb
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
In kernel/resource.c (ffffffff8108b751)
Location: include/linux/mm.h:596
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bfa3f)
Location: include/linux/mm.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/list_lru.c (ffffffff811edda1)
Location: include/linux/mm.h:596
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff81228f03)
Location: include/linux/mm.h:596
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/usercopy.c (ffffffff8124c89f)
Location: include/linux/mm.h:596
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bad73)
Location: include/linux/mm.h:596
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb
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
In kernel/resource.c (ffffffff810924d1)
Location: include/linux/mm.h:613
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d4573)
Location: include/linux/mm.h:613
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/list_lru.c (ffffffff81204201)
Location: include/linux/mm.h:613
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff81242df3)
Location: include/linux/mm.h:613
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/usercopy.c (ffffffff8126cd5f)
Location: include/linux/mm.h:613
Inline: True
```
```
In net/core/skbuff.c (ffffffff81832e4d)
Location: include/linux/mm.h:613
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb
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
In kernel/resource.c (ffffffff81095eae)
Location: include/linux/mm.h:655
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f5f85)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/list_lru.c (ffffffff81224eae)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff812687c4)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/usercopy.c (ffffffff812919af)
Location: include/linux/mm.h:655
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187d36d)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff818ba9e0)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff819cb534)
Location: include/linux/mm.h:655
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff8109e21e)
Location: include/linux/mm.h:683
Inline: True
```
```
In mm/page_alloc.c (ffffffff81209465)
Location: include/linux/mm.h:683
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/list_lru.c (ffffffff81237fbe)
Location: include/linux/mm.h:683
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff8127d264)
Location: include/linux/mm.h:683
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/usercopy.c (ffffffff812a69ec)
Location: include/linux/mm.h:683
Inline: True
```
```
In drivers/net/tun.c (ffffffff81763676)
Location: include/linux/mm.h:683
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8189df4b)
Location: include/linux/mm.h:683
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff818e1926)
Location: include/linux/mm.h:683
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81a04785)
Location: include/linux/mm.h:683
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810a278c)
Location: include/linux/mm.h:749
Inline: True
```
```
In mm/list_lru.c (ffffffff81249570)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff81270775)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812988c6)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffffffff812b27b5)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/usercopy.c (ffffffff812c20d1)
Location: include/linux/mm.h:749
Inline: True
```
```
In fs/io_uring.c (ffffffff8132dfdf)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffffffff817a13a3)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818e871a)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81930099)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81a74cb6)
Location: include/linux/mm.h:749
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810a8d5c)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (ffffffff812579c0)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff8127f5b5)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812a8726)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffffffff812c6ede)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (ffffffff81341215)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffffffff817c6363)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8191a95a)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff819622f9)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81aab886)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810b018c)
Location: include/linux/mm.h:839
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b1505)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812ddab9)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:cache_from_obj
```
```
In mm/memcontrol.c (ffffffff812fc7fe)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In fs/io_uring.c (ffffffff8137c312)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/net/tun.c (ffffffff8188b5ab)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff819ecf59)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81a3642b)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81ba7196)
Location: include/linux/mm.h:839
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810ab8ac)
Location: include/linux/mm.h:872
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bd5e5)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812e68cb)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81308ade)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In fs/io_uring.c (ffffffff8138a4e2)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/net/tun.c (ffffffff8189974f)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff819ecc19)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81a3828d)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3d29b)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/xdp/xsk.c (ffffffff81bb6909)
Location: include/linux/mm.h:872
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810acc2c)
Location: include/linux/mm.h:895
Inline: True
```
```
In mm/slab_common.c (ffffffff8128d503)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/page_alloc.c (ffffffff812c2575)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812ee08b)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130f221)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In fs/io_uring.c (ffffffff813915a1)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/net/tun.c (ffffffff8187bbc4)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff819d30ec)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81a1f88d)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a240bb)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/xdp/xsk.c (ffffffff81ba58a9)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810be79c)
Location: include/linux/mm.h:898
Inline: True
```
```
In mm/slab_common.c (ffffffff812cc9a7)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/page_alloc.c (ffffffff81305f45)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff81336469)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8135a09a)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In fs/io_uring.c (ffffffff813df3a8)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In drivers/net/tun.c (ffffffff8190d0f4)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81a82df6)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81ad384d)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81ad868b)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/xdp/xsk.c (ffffffff81c73454)
Location: include/linux/mm.h:898
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *virt_to_head_page(const void *x);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5cd5)
Location: include/linux/mm.h:844
Inline: True
```
```
In mm/page_alloc.c (ffffffff8136dfc5)
Location: include/linux/mm.h:844
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In io_uring/io_uring.c (ffffffff81e8e3c0)
Location: include/linux/mm.h:844
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In drivers/net/tun.c (ffffffff81a63a06)
Location: include/linux/mm.h:844
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81bf7b9e)
Location: include/linux/mm.h:844
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81c51159)
Location: include/linux/mm.h:844
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c54c46)
Location: include/linux/mm.h:844
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c59574)
Location: include/linux/mm.h:844
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/xdp/xsk.c (ffffffff81e15fc4)
Location: include/linux/mm.h:844
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
**Symbols:**

```
ffffffff81e8e3c0-ffffffff81e8e404: virt_to_head_page (STB_LOCAL)
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
In kernel/resource.c (ffffffff810f4f85)
Location: include/linux/mm.h:955
Inline: True
```
```
In mm/page_alloc.c (ffffffff813ea305)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In io_uring/io_uring.c (ffffffff81789bcf)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In drivers/net/tun.c (ffffffff81bf2be6)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/skbuff.c (ffffffff81da68fe)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81e06938)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e0a3d1)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e0f554)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/xdp/xsk.c (ffffffff81fed011)
Location: include/linux/mm.h:955
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff811013b5)
Location: include/linux/mm.h:1200
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141f2e5)
Location: include/linux/mm.h:1200
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In io_uring/io_uring.c (ffffffff817c99c7)
Location: include/linux/mm.h:1200
Inline: True
```
```
In io_uring/kbuf.c (ffffffff817e00d6)
Location: include/linux/mm.h:1200
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c4a193)
Location: include/linux/mm.h:1200
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c53f0a)
Location: include/linux/mm.h:1200
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
```
```
In net/core/skbuff.c (ffffffff81e159a6)
Location: include/linux/mm.h:1200
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81e79670)
Location: include/linux/mm.h:1200
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7cbad)
Location: include/linux/mm.h:1200
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e82d27)
Location: include/linux/mm.h:1200
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
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
In kernel/resource.c (ffffffff8110aae5)
Location: include/linux/mm.h:1283
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144bfa5)
Location: include/linux/mm.h:1283
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In io_uring/io_uring.c (ffffffff8180f55e)
Location: include/linux/mm.h:1283
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cffb1f)
Location: include/linux/mm.h:1283
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d08a73)
Location: include/linux/mm.h:1283
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:virtnet_rq_unmap
```
```
In net/core/skbuff.c (ffffffff81ed2d3a)
Location: include/linux/mm.h:1283
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81f39722)
Location: include/linux/mm.h:1283
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3cefd)
Location: include/linux/mm.h:1283
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f43b12)
Location: include/linux/mm.h:1283
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
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
In kernel/resource.c (ffff80001010008c)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (ffff8000102ef548)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffff800010317240)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffff80001034a0e4)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffff800010369c9c)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (ffff800010400348)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffff8000109e1480)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e2b30)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
```
```
In net/core/skbuff.c (ffff800010bb4cc4)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffff800010c065d0)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffff800010d7df70)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (c035cc58)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (c0512f78)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (c053193c)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (c054e9d8)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (c055b008)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (c05d26e0)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (c0ac660c)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c0cd1dd8)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (c0d1f6a4)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (c0e78b04)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (c000000000147c90)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (c0000000003b3b80)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (c0000000003e95c0)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (c000000000428fd8)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (c000000000458824)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (c000000000509a68)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (c000000000aa316c)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (c000000000c8ba30)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (c000000000cf0ab4)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (c000000000ebdb34)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffe0000c801e)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (ffffffe000203214)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffe00021d49a)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffe00023ba68)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffffffe000247536)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (ffffffe0002acab0)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffffffe00062afd2)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffe000744cf2)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffe000784b6e)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffe0008ab764)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810a267c)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (ffffffff81250010)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff81277c05)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812a0d06)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffffffff812bf4be)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (ffffffff813397f5)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffffffff8178ae43)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818ba95a)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff819022c9)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81a4ac16)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff8109105c)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (ffffffff81242fb0)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff81269b15)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812927e6)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffffffff812b05ae)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (ffffffff8132a525)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffffffff8176a793)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff818748aa)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff818bc0f9)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81a07806)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810a262c)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (ffffffff8124ddb0)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff812759a5)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff8129eb16)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffffffff812bd2ce)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (ffffffff813372c5)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffffffff817bb1e3)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8190b95a)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff819532f9)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81ab6ac6)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/resource.c (ffffffff810aa66c)
Location: include/linux/mm.h:744
Inline: True
```
```
In mm/list_lru.c (ffffffff8125d75b)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff81285565)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/slub.c (ffffffff812aebf6)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memcontrol.c (ffffffff812cdb2e)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In fs/io_uring.c (ffffffff8134a385)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In drivers/net/tun.c (ffffffff817d4219)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/skbuff.c (ffffffff8192ca7a)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81974e01)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff81ac2c06)
Location: include/linux/mm.h:744
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
