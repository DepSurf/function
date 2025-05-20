# Function: <code>tcp_send_synack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817792e0)
Location: net/ipv4/tcp_output.c:2904
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff817792e0-ffffffff81779525: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e64a0)
Location: net/ipv4/tcp_output.c:2948
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff817e64a0-ffffffff817e66f0: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81816be0)
Location: net/ipv4/tcp_output.c:3072
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81816be0-ffffffff81816e30: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81836f20)
Location: net/ipv4/tcp_output.c:3097
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81836f20-ffffffff81837246: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b65e0)
Location: net/ipv4/tcp_output.c:3152
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff818b65e0-ffffffff818b68f5: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3133
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff8190c540-ffffffff8190c55d: tcp_send_synack.cold.53 (STB_LOCAL)
ffffffff8190be20-ffffffff8190c141: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3165
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff8193a88a-ffffffff8193a8a7: tcp_send_synack.cold.56 (STB_LOCAL)
ffffffff8193a100-ffffffff8193a41b: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3192
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff8199ec36-ffffffff8199ec53: tcp_send_synack.cold (STB_LOCAL)
ffffffff8199e3a0-ffffffff8199e74a: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff819d56e2-ffffffff819d56ff: tcp_send_synack.cold (STB_LOCAL)
ffffffff819d4e80-ffffffff819d5251: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3296
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81ac2022-ffffffff81ac203f: tcp_send_synack.cold (STB_LOCAL)
ffffffff81ac1840-ffffffff81ac1bbc: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3468
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81c326da-ffffffff81c326f7: tcp_send_synack.cold (STB_LOCAL)
ffffffff81acd2b0-ffffffff81acd619: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3465
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81c249af-ffffffff81c249cc: tcp_send_synack.cold (STB_LOCAL)
ffffffff81ab8480-ffffffff81ab87ec: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3466
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81d3b3c3-ffffffff81d3b459: tcp_send_synack.cold (STB_LOCAL)
ffffffff81b75670-ffffffff81b75a02: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3472
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81f07cab-ffffffff81f07d42: tcp_send_synack.cold (STB_LOCAL)
ffffffff81d04f10-ffffffff81d052ba: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3474
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff820af713-ffffffff820af78d: tcp_send_synack.cold (STB_LOCAL)
ffffffff81ec9f80-ffffffff81eca37a: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3556
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff82130adb-ffffffff82130b3f: tcp_send_synack.cold (STB_LOCAL)
ffffffff81f28ad0-ffffffff81f28eb9: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3620
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff822122af-ffffffff82212313: tcp_send_synack.cold (STB_LOCAL)
ffffffff81fed570-ffffffff81fed962: tcp_send_synack (STB_GLOBAL)
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
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c87b20)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffff800010c87b20-ffff800010c87ec8: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d96e64)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
c0d96e64-c0d97224: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d947d0)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
c000000000d947d0-c000000000d94c68: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e8e3a)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffe0007e8e3a-ffffffe0007e9168: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81975552-ffffffff8197556f: tcp_send_synack.cold (STB_LOCAL)
ffffffff81974cf0-ffffffff819750c1: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff8192f012-ffffffff8192f02f: tcp_send_synack.cold (STB_LOCAL)
ffffffff8192e7b0-ffffffff8192eb81: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff819dfd22-ffffffff819dfd3f: tcp_send_synack.cold (STB_LOCAL)
ffffffff819df4c0-ffffffff819df891: tcp_send_synack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tcp_send_synack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3223
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff819e99d5-ffffffff819e99f2: tcp_send_synack.cold (STB_LOCAL)
ffffffff819e9170-ffffffff819e9541: tcp_send_synack (STB_GLOBAL)
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
