# Function: <code>tcp_time_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff8177fe70)
Location: net/ipv4/tcp_minisocks.c:267
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff8177fe70-ffffffff8178012a: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff817ed390)
Location: net/ipv4/tcp_minisocks.c:261
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff817ed390-ffffffff817ed611: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff8181dca0)
Location: net/ipv4/tcp_minisocks.c:261
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff8181dca0-ffffffff8181df21: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff8183e430)
Location: net/ipv4/tcp_minisocks.c:252
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff8183e430-ffffffff8183e688: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff818bdc60)
Location: net/ipv4/tcp_minisocks.c:251
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff818bdc60-ffffffff818bdede: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff819126a0)
Location: net/ipv4/tcp_minisocks.c:252
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff819126a0-ffffffff81912914: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81940e70)
Location: net/ipv4/tcp_minisocks.c:252
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81940e70-ffffffff819410e3: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff819a5490)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff819a5490-ffffffff819a5732: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff819dc170)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff819dc170-ffffffff819dc421: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81ac92d0)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81ac92d0-ffffffff81ac9581: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5220)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81ad5220-ffffffff81ad54d1: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81ac02a0)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81ac02a0-ffffffff81ac054e: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81d3bb0b-ffffffff81d3bb2d: tcp_time_wait.cold (STB_LOCAL)
ffffffff81b7f230-ffffffff81b7f4ec: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:246
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81f0826d-ffffffff81f0828f: tcp_time_wait.cold (STB_LOCAL)
ffffffff81d0ebe0-ffffffff81d0eea0: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff820afd51-ffffffff820afd7b: tcp_time_wait.cold (STB_LOCAL)
ffffffff81ed46d0-ffffffff81ed49e5: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff82130f95-ffffffff82130fae: tcp_time_wait.cold (STB_LOCAL)
ffffffff81f32530-ffffffff81f32804: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_minisocks.c (0)
Location: net/ipv4/tcp_minisocks.c:292
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff82212911-ffffffff8221292a: tcp_time_wait.cold (STB_LOCAL)
ffffffff81ff8510-ffffffff81ff881d: tcp_time_wait (STB_GLOBAL)
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
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffff800010c900d0)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffff800010c900d0-ffff800010c90338: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (c0d9e2f8)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
c0d9e2f8-c0d9e540: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (c000000000d9e090)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
c000000000d9e090-c000000000d9e3a8: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef594)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffe0007ef594-ffffffe0007ef808: tcp_time_wait (STB_GLOBAL)
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
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff8197bfe0)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff8197bfe0-ffffffff8197c291: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81935aa0)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81935aa0-ffffffff81935d51: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff819e67b0)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff819e67b0-ffffffff819e6a61: tcp_time_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_time_wait(struct sock *sk, int state, int timeo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff819f0470)
Location: net/ipv4/tcp_minisocks.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff819f0470-ffffffff819f0721: tcp_time_wait (STB_GLOBAL)
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
