# Function: <code>tcp_enter_quickack_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176a6f7)
Location: net/ipv4/tcp_input.c:189
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817e0a75)
Location: net/ipv4/tcp_input.c:191
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81810e7a)
Location: net/ipv4/tcp_input.c:212
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81830a4c)
Location: net/ipv4/tcp_input.c:211
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818afeb8)
Location: net/ipv4/tcp_input.c:197
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8190596b)
Location: net/ipv4/tcp_input.c:218
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff818fc1a0-ffffffff818fc1f5: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81933b0d)
Location: net/ipv4/tcp_input.c:219
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff8192a1e0-ffffffff8192a235: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8199729a)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff8198d420-ffffffff8198d475: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cde1a)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff819c3d80-ffffffff819c3dd5: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab9fe0)
Location: net/ipv4/tcp_input.c:226
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff81aaf550-ffffffff81aaf5a5: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac5422)
Location: net/ipv4/tcp_input.c:289
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff81aba5a0-ffffffff81aba5f5: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0646)
Location: net/ipv4/tcp_input.c:289
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff81aa5890-ffffffff81aa58e5: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6d476)
Location: net/ipv4/tcp_input.c:290
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff81b61be0-ffffffff81b61c35: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cfcac5)
Location: net/ipv4/tcp_input.c:290
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff81cf0650-ffffffff81cf06b6: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ec1675)
Location: net/ipv4/tcp_input.c:290
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff81eb4c80-ffffffff81eb4ce6: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1fbd4)
Location: net/ipv4/tcp_input.c:290
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe43de)
Location: net/ipv4/tcp_input.c:306
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
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
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c808f4)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffff800010c769b8-ffff800010c76a20: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8fac0)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
c0d84f10-c0d84f74: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d8b5c4)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
c000000000d7e4b0-c000000000d7e50c: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e2878)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffe0007d9932-ffffffe0007d9990: tcp_enter_quickack_mode (STB_GLOBAL)
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
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196dc8a)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff81963bf0-ffffffff81963c45: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192777a)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff8191d6e0-ffffffff8191d735: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d845a)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff819ce3c0-ffffffff819ce415: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_quickack_mode(struct sock *sk, unsigned int max_quickacks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e209a)
Location: net/ipv4/tcp_input.c:225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
**Symbols:**

```
ffffffff819d7f50-ffffffff819d7fa5: tcp_enter_quickack_mode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
