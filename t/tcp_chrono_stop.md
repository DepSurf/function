# Function: <code>tcp_chrono_stop</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81813040)
Location: net/ipv4/tcp_output.c:2139
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81813040-ffffffff818130da: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81833270)
Location: net/ipv4/tcp_output.c:2226
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81833270-ffffffff818332fd: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b25a0)
Location: net/ipv4/tcp_output.c:2277
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818b25a0-ffffffff818b2642: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81907aa0)
Location: net/ipv4/tcp_output.c:2260
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81907aa0-ffffffff81907b39: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81935d30)
Location: net/ipv4/tcp_output.c:2286
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81935d30-ffffffff81935dc9: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199a0c0)
Location: net/ipv4/tcp_output.c:2314
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff8199a0c0-ffffffff8199a159: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d0ad0)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819d0ad0-ffffffff819d0b69: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abdcb0)
Location: net/ipv4/tcp_output.c:2396
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81abdcb0-ffffffff81abdd47: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac9590)
Location: net/ipv4/tcp_output.c:2566
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ac9590-ffffffff81ac9627: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab4440)
Location: net/ipv4/tcp_output.c:2567
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ab4440-ffffffff81ab44da: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b71340)
Location: net/ipv4/tcp_output.c:2567
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81b71340-ffffffff81b7144f: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d00830)
Location: net/ipv4/tcp_output.c:2567
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81d00830-ffffffff81d00976: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec5960)
Location: net/ipv4/tcp_output.c:2569
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ec5960-ffffffff81ec5aa6: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f23f40)
Location: net/ipv4/tcp_output.c:2611
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81f23f40-ffffffff81f2405a: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe8750)
Location: net/ipv4/tcp_output.c:2668
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81fe8750-ffffffff81fe886a: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c83738)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffff800010c83738-ffff800010c83814: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d92928)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
c0d92928-c0d929ec: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8efc0)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
c000000000d8efc0-c000000000d8f09c: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e52b2)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffe0007e52b2-ffffffe0007e5382: tcp_chrono_stop (STB_GLOBAL)
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
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81970940)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81970940-ffffffff819709d9: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192a410)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff8192a410-ffffffff8192a4a9: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819db110)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819db110-ffffffff819db1a9: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_chrono_stop(struct sock *sk, const enum tcp_chrono type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e4d90)
Location: net/ipv4/tcp_output.c:2333
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819e4d90-ffffffff819e4e29: tcp_chrono_stop (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
