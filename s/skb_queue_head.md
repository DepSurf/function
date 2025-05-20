# Function: <code>skb_queue_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81704f90)
Location: net/core/skbuff.c:2460
Inline: False
Direct callers:
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81704f90-ffffffff81704fd9: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176bb60)
Location: net/core/skbuff.c:2458
Inline: False
Direct callers:
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff8176bb60-ffffffff8176bba9: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81798c30)
Location: net/core/skbuff.c:2453
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81798c30-ffffffff81798c79: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b71e0)
Location: net/core/skbuff.c:2493
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff817b71e0-ffffffff817b7229: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182f7e0)
Location: net/core/skbuff.c:2872
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff8182f7e0-ffffffff8182f829: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879d00)
Location: net/core/skbuff.c:2888
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81879d00-ffffffff81879d49: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189a970)
Location: net/core/skbuff.c:2947
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff8189a970-ffffffff8189a9b9: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e4f90)
Location: net/core/skbuff.c:3113
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff818e4f90-ffffffff818e4fd9: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917120)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81917120-ffffffff81917169: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9aa0)
Location: net/core/skbuff.c:3118
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_sqe_files_scm
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff819e9aa0-ffffffff819e9ae9: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9840)
Location: net/core/skbuff.c:3136
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_sqe_files_scm
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff819e9840-ffffffff819e9889: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819cf960)
Location: net/core/skbuff.c:3222
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_sqe_files_scm
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff819cf960-ffffffff819cf9a9: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7f4b0)
Location: net/core/skbuff.c:3294
Inline: False
Direct callers:
  - fs/io_uring.c:__io_sqe_files_scm
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81a7f4b0-ffffffff81a7f4fe: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf37f0)
Location: net/core/skbuff.c:3343
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81bf37f0-ffffffff81bf3848: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1580)
Location: net/core/skbuff.c:3547
Inline: False
Direct callers:
  - io_uring/rsrc.c:__io_scm_file_account
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81da1580-ffffffff81da15d8: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e0fe70)
Location: net/core/skbuff.c:3717
Inline: False
Direct callers:
  - io_uring/rsrc.c:__io_scm_file_account
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81e0fe70-ffffffff81e0fec8: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecc920)
Location: net/core/skbuff.c:3838
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81ecc920-ffffffff81ecc978: skb_queue_head (STB_GLOBAL)
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
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3a00)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffff800010bb3a00-ffff800010bb3ac8: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccdb10)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__se_sys_io_uring_register
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
c0ccdb10-c0ccdb68: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c86270)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__se_sys_io_uring_register
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
c000000000c86270-c000000000c862fc: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741574)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__se_sys_io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffe000741574-ffffffe0007415d0: skb_queue_head (STB_GLOBAL)
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
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7120)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff818b7120-ffffffff818b7169: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871070)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81871070-ffffffff818710b9: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908120)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81908120-ffffffff81908169: skb_queue_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929160)
Location: net/core/skbuff.c:3119
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_rehold_skb
  - fs/io_uring.c:__io_uring_register
  - net/core/netpoll.c:queue_process
```
**Symbols:**

```
ffffffff81929160-ffffffff819291a9: skb_queue_head (STB_GLOBAL)
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
