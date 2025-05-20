# Function: <code>skb_to_sgvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705970)
Location: net/core/skbuff.c:3499
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff81705970-ffffffff8170599f: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c640)
Location: net/core/skbuff.c:3540
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff8176c640-ffffffff8176c66f: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a080)
Location: net/core/skbuff.c:3566
Inline: False
```
**Symbols:**

```
ffffffff8179a080-ffffffff8179a0af: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b9720)
Location: net/core/skbuff.c:3605
Inline: False
```
**Symbols:**

```
ffffffff817b9720-ffffffff817b9756: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81831f70)
Location: net/core/skbuff.c:3989
Inline: False
```
**Symbols:**

```
ffffffff81831f70-ffffffff81831fa6: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187c630)
Location: net/core/skbuff.c:4028
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_tx_work
```
**Symbols:**

```
ffffffff8187c630-ffffffff8187c666: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189cfb0)
Location: net/core/skbuff.c:4048
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff8189cfb0-ffffffff8189cfe6: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e7760)
Location: net/core/skbuff.c:4233
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff818e7760-ffffffff818e7796: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919a70)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81919a70-ffffffff81919aa6: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea940)
Location: net/core/skbuff.c:4347
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
```
**Symbols:**

```
ffffffff819ea940-ffffffff819ea97a: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea680)
Location: net/core/skbuff.c:4414
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
**Symbols:**

```
ffffffff819ea680-ffffffff819ea6ba: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0c40)
Location: net/core/skbuff.c:4500
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
**Symbols:**

```
ffffffff819d0c40-ffffffff819d0c7a: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7fdf0)
Location: net/core/skbuff.c:4568
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
**Symbols:**

```
ffffffff81a7fdf0-ffffffff81a7fe2a: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4310)
Location: net/core/skbuff.c:4484
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
**Symbols:**

```
ffffffff81bf4310-ffffffff81bf4359: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2130)
Location: net/core/skbuff.c:4686
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
**Symbols:**

```
ffffffff81da2130-ffffffff81da2179: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e10a00)
Location: net/core/skbuff.c:4877
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
**Symbols:**

```
ffffffff81e10a00-ffffffff81e10a49: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecd520)
Location: net/core/skbuff.c:5003
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:xmit_skb
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
**Symbols:**

```
ffffffff81ecd520-ffffffff81ecd569: skb_to_sgvec (STB_GLOBAL)
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
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb2b38)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffff800010bb2b38-ffff800010bb2bac: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd105c)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
c0cd105c-c0cd10b0: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8aca0)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
c000000000c8aca0-c000000000c8ad00: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000743fce)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffe000743fce-ffffffe00074402c: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9a70)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff818b9a70-ffffffff818b9aa6: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818739c0)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff818739c0-ffffffff818739f6: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190aa70)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff8190aa70-ffffffff8190aaa6: skb_to_sgvec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192bb70)
Location: net/core/skbuff.c:4245
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff8192bb70-ffffffff8192bba6: skb_to_sgvec (STB_GLOBAL)
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
