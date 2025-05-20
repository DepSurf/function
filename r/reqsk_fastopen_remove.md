# Function: <code>reqsk_fastopen_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81704c00)
Location: net/core/request_sock.c:97
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81704c00-ffffffff81704d61: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8176b7f0)
Location: net/core/request_sock.c:97
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff8176b7f0-ffffffff8176b948: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff817988c0)
Location: net/core/request_sock.c:97
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff817988c0-ffffffff81798a18: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff817b6ea0)
Location: net/core/request_sock.c:95
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff817b6ea0-ffffffff817b6fdc: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8182f490)
Location: net/core/request_sock.c:95
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff8182f490-ffffffff8182f5de: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81879920)
Location: net/core/request_sock.c:95
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81879920-ffffffff81879a65: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff8189a570)
Location: net/core/request_sock.c:95
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff8189a570-ffffffff8189a6b5: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818e4c50)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff818e4c50-ffffffff818e4d97: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81916de0)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81916de0-ffffffff81916f27: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819e9760)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff819e9760-ffffffff819e98ed: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819e9500)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff819e9500-ffffffff819e968d: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff819cf620)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff819cf620-ffffffff819cf7ad: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81a7f160)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81a7f160-ffffffff81a7f2ed: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81bf3410)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81bf3410-ffffffff81bf35a2: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81da1170)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81da1170-ffffffff81da1302: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81e0fa40)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81e0fa40-ffffffff81e0fbd2: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81ecc4f0)
Location: net/core/request_sock.c:88
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81ecc4f0-ffffffff81ecc682: reqsk_fastopen_remove (STB_GLOBAL)
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
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffff800010bb0318)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffff800010bb0318-ffff800010bb04e4: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (c0ccd764)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
c0ccd764-c0ccd8c4: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (c000000000c85d70)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
c000000000c85d70-c000000000c85f50: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffe0007411fa)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffe0007411fa-ffffffe000741316: reqsk_fastopen_remove (STB_GLOBAL)
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
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff818b6de0)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff818b6de0-ffffffff818b6f27: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81870d30)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81870d30-ffffffff81870e77: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81907de0)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81907de0-ffffffff81907f27: reqsk_fastopen_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reqsk_fastopen_remove(struct sock *sk, struct request_sock *req, bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/request_sock.c (ffffffff81928e20)
Location: net/core/request_sock.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
**Symbols:**

```
ffffffff81928e20-ffffffff81928f67: reqsk_fastopen_remove (STB_GLOBAL)
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
