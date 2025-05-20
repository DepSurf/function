# Function: <code>build_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8170be10)
Location: net/core/skbuff.c:339
Inline: False
```
**Symbols:**

```
ffffffff8170be10-ffffffff8170be91: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81773800)
Location: net/core/skbuff.c:340
Inline: False
```
**Symbols:**

```
ffffffff81773800-ffffffff81773888: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817a0a30)
Location: net/core/skbuff.c:340
Inline: False
```
**Symbols:**

```
ffffffff817a0a30-ffffffff817a0ab2: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bb150)
Location: net/core/skbuff.c:339
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff817bb150-ffffffff817bb1d2: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818331c0)
Location: net/core/skbuff.c:310
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
  - drivers/net/tun.c:tun_get_user
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818331c0-ffffffff81833242: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187d660)
Location: net/core/skbuff.c:310
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8187d660-ffffffff8187d6e2: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189e290)
Location: net/core/skbuff.c:313
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8189e290-ffffffff8189e30c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e8aa0)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818e8aa0-ffffffff818e8b1c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191ac00)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8191ac00-ffffffff8191ac7c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed1e0)
Location: net/core/skbuff.c:325
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819ed1e0-ffffffff819ed25c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ecea0)
Location: net/core/skbuff.c:330
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819ecea0-ffffffff819ecf1c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d3370)
Location: net/core/skbuff.c:254
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819d3370-ffffffff819d33ec: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a830a0)
Location: net/core/skbuff.c:256
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_build_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a830a0-ffffffff81a8311b: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf7ea0)
Location: net/core/skbuff.c:254
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81bf7ea0-ffffffff81bf7f5c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da6c40)
Location: net/core/skbuff.c:392
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
```
**Symbols:**

```
ffffffff81da6c40-ffffffff81da6cfc: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e15e90)
Location: net/core/skbuff.c:461
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
```
**Symbols:**

```
ffffffff81e15e90-ffffffff81e15f41: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed32c0)
Location: net/core/skbuff.c:462
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:page_to_skb
```
**Symbols:**

```
ffffffff81ed32c0-ffffffff81ed336e: build_skb (STB_GLOBAL)
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
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb4f10)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffff800010bb4f10-ffff800010bb4fa4: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd2024)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c0cd2024-c0cd209c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8be30)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c000000000c8be30-c000000000c8bf08: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000745018)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffe000745018-ffffffe0007450a0: build_skb (STB_GLOBAL)
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
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bac00)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818bac00-ffffffff818bac7c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81874b50)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81874b50-ffffffff81874bcc: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190bc00)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8190bc00-ffffffff8190bc7c: build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192cd20)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8192cd20-ffffffff8192cd9c: build_skb (STB_GLOBAL)
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
