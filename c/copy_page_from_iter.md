# Function: <code>copy_page_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fce90)
Location: lib/iov_iter.c:462
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff813fce90-ffffffff813fcf21: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814450c0)
Location: lib/iov_iter.c:417
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff814450c0-ffffffff8144514a: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81463a80)
Location: lib/iov_iter.c:657
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff81463a80-ffffffff81463b23: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81467a30)
Location: lib/iov_iter.c:714
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff81467a30-ffffffff81467c1e: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81493cb0)
Location: lib/iov_iter.c:716
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff81493cb0-ffffffff81493ed0: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c8fb0)
Location: lib/iov_iter.c:846
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff814c8fb0-ffffffff814c91dc: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814dd730)
Location: lib/iov_iter.c:892
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff814dd730-ffffffff814dd967: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:906
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff8150addd-ffffffff8150ae0c: copy_page_from_iter.cold (STB_LOCAL)
ffffffff815089c0-ffffffff81508bf7: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81527340)
Location: lib/iov_iter.c:906
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff81527340-ffffffff8152755e: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8158bf00)
Location: lib/iov_iter.c:927
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw_single_vec
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_from_iter
  - drivers/net/tun.c:tun_build_skb
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff8158bf00-ffffffff8158bfd8: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a6de0)
Location: lib/iov_iter.c:934
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_from_iter
  - drivers/net/tun.c:tun_build_skb
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff815a6de0-ffffffff815a6eb8: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815afab0)
Location: lib/iov_iter.c:1004
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_user_iov
  - drivers/net/tun.c:tun_build_skb
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff815afab0-ffffffff815afd1b: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:851
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_user_iov
  - drivers/net/tun.c:tun_build_skb
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81cda947-ffffffff81cda970: copy_page_from_iter.cold (STB_LOCAL)
ffffffff81616d20-ffffffff81616f8f: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e52e0)
Location: lib/iov_iter.c:903
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff816e52e0-ffffffff816e54e7: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d3ab0)
Location: lib/iov_iter.c:743
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff817d3ab0-ffffffff817d3b67: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff81812311)
Location: lib/iov_iter.c:531
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff820f85da-ffffffff820f85f3: copy_page_from_iter.cold (STB_LOCAL)
ffffffff818122e0-ffffffff81812424: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff81858971)
Location: lib/iov_iter.c:411
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - block/blk-map.c:bio_copy_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
**Symbols:**

```
ffffffff821d62ca-ffffffff821d62e0: copy_page_from_iter.cold (STB_LOCAL)
ffffffff81858940-ffffffff81858a84: copy_page_from_iter (STB_GLOBAL)
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
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff800010631a80)
Location: lib/iov_iter.c:906
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffff800010631a80-ffff800010631cd0: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d9264)
Location: lib/iov_iter.c:906
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
c07d9264-c07d9708: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d74c0)
Location: lib/iov_iter.c:906
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
c0000000007d74c0-c0000000007d77e4: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe0004605f6)
Location: lib/iov_iter.c:906
Inline: False
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffe0004605f6-ffffffe0004607d2: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151f920)
Location: lib/iov_iter.c:906
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff8151f920-ffffffff8151fb3e: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150fc10)
Location: lib/iov_iter.c:906
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff8150fc10-ffffffff8150fe2e: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151b9b0)
Location: lib/iov_iter.c:906
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff8151b9b0-ffffffff8151bbce: copy_page_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t copy_page_from_iter(struct page *page, size_t offset, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815351f0)
Location: lib/iov_iter.c:906
Inline: True
Direct callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/fuse/file.c:fuse_do_ioctl
  - block/bio.c:bio_copy_user_iov
  - net/core/datagram.c:skb_copy_datagram_from_iter
```
**Symbols:**

```
ffffffff815351f0-ffffffff81535417: copy_page_from_iter (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
