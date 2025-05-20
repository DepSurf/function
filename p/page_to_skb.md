# Function: <code>page_to_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *page_to_skb(struct virtnet_info *vi, struct receive_queue *rq, struct page *page, unsigned int offset, unsigned int len, unsigned int truesize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f0ee0)
Location: drivers/net/virtio_net.c:246
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
**Symbols:**

```
ffffffff815f0ee0-ffffffff815f11f4: page_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81650d30)
Location: drivers/net/virtio_net.c:252
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
**Symbols:**

```
ffffffff81650d30-ffffffff81651025: page_to_skb.isra.28 (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *page_to_skb(struct virtnet_info *vi, struct receive_queue *rq, struct page *page, unsigned int offset, unsigned int len, unsigned int truesize, unsigned int headroom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:465
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
```
**Symbols:**

```
ffffffff81c53340-ffffffff81c53956: page_to_skb (STB_LOCAL)
ffffffff8211ea61-ffffffff8211ead2: page_to_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *page_to_skb(struct virtnet_info *vi, struct receive_queue *rq, struct page *page, unsigned int offset, unsigned int len, unsigned int truesize, unsigned int headroom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/virtio_net.c (0)
Location: drivers/net/virtio_net.c:526
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
```
**Symbols:**

```
ffffffff81d09af0-ffffffff81d0a10a: page_to_skb (STB_LOCAL)
ffffffff822001f8-ffffffff82200269: page_to_skb.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
