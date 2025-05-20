# Function: <code>kauditd_send_queue</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133c80)
Location: kernel/audit.c:681
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81133c80-ffffffff81133d7a: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81140a30)
Location: kernel/audit.c:681
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81140a30-ffffffff81140b38: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8114f370)
Location: kernel/audit.c:724
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8114f370-ffffffff8114f478: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115c050)
Location: kernel/audit.c:720
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8115c050-ffffffff8115c158: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81168700)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81168700-ffffffff8116881e: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811745a0)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811745a0-ffffffff811746be: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81186730)
Location: kernel/audit.c:709
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81186730-ffffffff8118687c: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811838f0)
Location: kernel/audit.c:714
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811838f0-ffffffff81183a3c: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184960)
Location: kernel/audit.c:714
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81184960-ffffffff81184aa5: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811acb90)
Location: kernel/audit.c:736
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811acb90-ffffffff811acceb: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811de750)
Location: kernel/audit.c:737
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff811de750-ffffffff811de8f1: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81224300)
Location: kernel/audit.c:735
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81224300-ffffffff812244a1: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123a8e0)
Location: kernel/audit.c:735
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8123a8e0-ffffffff8123aa7d: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *, int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff812545d0)
Location: kernel/audit.c:746
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff812545d0-ffffffff8125476d: kauditd_send_queue (STB_LOCAL)
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
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101e8fb0)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffff8000101e8fb0-ffff8000101e90c8: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c0428fa0)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
c0428fa0-c04290ac: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c000000000259b60)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
c000000000259b60-c000000000259d44: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015de9a)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffe00015de9a-ffffffe00015df98: kauditd_send_queue (STB_LOCAL)
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
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116cbc0)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8116cbc0-ffffffff8116ccde: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115fd60)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8115fd60-ffffffff8115fe7e: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116a990)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff8116a990-ffffffff8116aaae: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock *sk, u32 portid, struct sk_buff_head *queue, unsigned int retry_limit, void (*skb_hook)(struct sk_buff *), void (*err_hook)(struct sk_buff *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81178150)
Location: kernel/audit.c:707
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
```
**Symbols:**

```
ffffffff81178150-ffffffff8117826e: kauditd_send_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*err_hook)(struct sk_buff *)</code> ➡️ <code>void (*err_hook)(struct sk_buff *, int)</code>
</li>
</ul>
</details>
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
