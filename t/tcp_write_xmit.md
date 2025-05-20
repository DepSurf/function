# Function: <code>tcp_write_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81776720)
Location: net/ipv4/tcp_output.c:2020
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81776720-ffffffff817775ee: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e3680)
Location: net/ipv4/tcp_output.c:2039
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff817e3680-ffffffff817e4602: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81813d50)
Location: net/ipv4/tcp_output.c:2171
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81813d50-ffffffff81814cbe: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81833f90)
Location: net/ipv4/tcp_output.c:2258
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81833f90-ffffffff81834e5e: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b3390)
Location: net/ipv4/tcp_output.c:2309
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff818b3390-ffffffff818b42ca: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81908920)
Location: net/ipv4/tcp_output.c:2292
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81908920-ffffffff819098c1: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81936b60)
Location: net/ipv4/tcp_output.c:2318
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81936b60-ffffffff81937b61: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199c170)
Location: net/ipv4/tcp_output.c:2346
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff8199c170-ffffffff8199ccef: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d2c10)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819d2c10-ffffffff819d37a1: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abf7d0)
Location: net/ipv4/tcp_output.c:2428
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81abf7d0-ffffffff81abff05: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acb240)
Location: net/ipv4/tcp_output.c:2598
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81acb240-ffffffff81acb970: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab6270)
Location: net/ipv4/tcp_output.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81ab6270-ffffffff81ab6bd9: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81b732c0-ffffffff81b73dc5: tcp_write_xmit (STB_LOCAL)
ffffffff81d3b2df-ffffffff81d3b335: tcp_write_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81d02a70-ffffffff81d034ff: tcp_write_xmit (STB_LOCAL)
ffffffff81f07c02-ffffffff81f07c1c: tcp_write_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec7bb0)
Location: net/ipv4/tcp_output.c:2601
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81ec7bb0-ffffffff81ec8407: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f26480)
Location: net/ipv4/tcp_output.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81f26480-ffffffff81f26f30: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81feae60)
Location: net/ipv4/tcp_output.c:2700
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81feae60-ffffffff81feb918: tcp_write_xmit (STB_LOCAL)
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
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c857e0)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffff800010c857e0-ffff800010c862ac: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d94a08)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
c0d94a08-c0d955f8: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d91950)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
c000000000d91950-c000000000d92768: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e700c)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffe0007e700c-ffffffe0007e7940: tcp_write_xmit (STB_LOCAL)
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
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81972a80)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81972a80-ffffffff81973611: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192c550)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff8192c550-ffffffff8192d0e1: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819dd250)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819dd250-ffffffff819ddde1: tcp_write_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock *sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e6ed0)
Location: net/ipv4/tcp_output.c:2365
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_push_one
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819e6ed0-ffffffff819e7a61: tcp_write_xmit (STB_LOCAL)
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
