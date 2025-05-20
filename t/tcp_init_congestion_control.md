# Function: <code>tcp_init_congestion_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81780770)
Location: net/ipv4/tcp_cong.c:182
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81780770-ffffffff81780822: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff817edc50)
Location: net/ipv4/tcp_cong.c:182
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff817edc50-ffffffff817edd02: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8181e5d0)
Location: net/ipv4/tcp_cong.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff8181e5d0-ffffffff8181e682: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8183ed20)
Location: net/ipv4/tcp_cong.c:179
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff8183ed20-ffffffff8183edea: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff818be550)
Location: net/ipv4/tcp_cong.c:176
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff818be550-ffffffff818be61d: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81914140)
Location: net/ipv4/tcp_cong.c:176
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff81914140-ffffffff8191420a: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819428f0)
Location: net/ipv4/tcp_cong.c:176
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff819428f0-ffffffff819429ba: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819a6ec0)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff819a6ec0-ffffffff819a6f8a: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819ddb90)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff819ddb90-ffffffff819ddc5a: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81acae90)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff81acae90-ffffffff81acaf60: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ad6e50)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81ad6e50-ffffffff81ad6f2e: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ac1ef0)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81ac1ef0-ffffffff81ac1fd4: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81d3bbfa-ffffffff81d3bc7a: tcp_init_congestion_control.cold (STB_LOCAL)
ffffffff81b7fc40-ffffffff81b7fd50: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:187
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81f08438-ffffffff81f084b8: tcp_init_congestion_control.cold (STB_LOCAL)
ffffffff81d0ff10-ffffffff81d1003c: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:187
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff820afed9-ffffffff820aff59: tcp_init_congestion_control.cold (STB_LOCAL)
ffffffff81ed5bc0-ffffffff81ed5cec: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:239
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff821311b4-ffffffff82131218: tcp_init_congestion_control.cold (STB_LOCAL)
ffffffff81f34af0-ffffffff81f34c15: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:239
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff82212b15-ffffffff82212b79: tcp_init_congestion_control.cold (STB_LOCAL)
ffffffff81ffac70-ffffffff81ffad95: tcp_init_congestion_control (STB_GLOBAL)
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
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffff800010c91068)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffff800010c91068-ffff800010c91148: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c0d9fcec)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
c0d9fcec-c0d9fdbc: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c000000000da0690)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
c000000000da0690-c000000000da07c8: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffe0007f0e6c)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffe0007f0e6c-ffffffe0007f0f3c: tcp_init_congestion_control (STB_GLOBAL)
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
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8197da00)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff8197da00-ffffffff8197daca: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819374c0)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff819374c0-ffffffff8193758a: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819e81d0)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff819e81d0-ffffffff819e829a: tcp_init_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819f1f00)
Location: net/ipv4/tcp_cong.c:177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff819f1f00-ffffffff819f1fca: tcp_init_congestion_control (STB_GLOBAL)
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
