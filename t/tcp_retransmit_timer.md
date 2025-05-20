# Function: <code>tcp_retransmit_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81779f20)
Location: net/ipv4/tcp_timer.c:363
Inline: True
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81779f20-ffffffff8177a64a: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff817e7130)
Location: net/ipv4/tcp_timer.c:404
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff817e7130-ffffffff817e794a: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81817870)
Location: net/ipv4/tcp_timer.c:409
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81817870-ffffffff81818100: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81837ce0)
Location: net/ipv4/tcp_timer.c:405
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81837ce0-ffffffff818385a6: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff818b7420)
Location: net/ipv4/tcp_timer.c:413
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff818b7420-ffffffff818b7cda: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8190cd80)
Location: net/ipv4/tcp_timer.c:405
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8190cd80-ffffffff8190d69c: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8193b090)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8193b090-ffffffff8193bab2: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8199f420)
Location: net/ipv4/tcp_timer.c:427
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8199f420-ffffffff8199feae: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff819d5fd0)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819d5fd0-ffffffff819d6a6e: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81ac2ef0)
Location: net/ipv4/tcp_timer.c:437
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81ac2ef0-ffffffff81ac3573: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81ace970)
Location: net/ipv4/tcp_timer.c:448
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81ace970-ffffffff81acefed: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81ab9b10)
Location: net/ipv4/tcp_timer.c:448
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81ab9b10-ffffffff81aba124: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:448
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81d3b5da-ffffffff81d3b613: tcp_retransmit_timer.cold (STB_LOCAL)
ffffffff81b76f40-ffffffff81b7755d: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:452
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81f07e93-ffffffff81f07ecd: tcp_retransmit_timer.cold (STB_LOCAL)
ffffffff81d06870-ffffffff81d06e55: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:446
Inline: False
```
**Symbols:**

```
ffffffff820af8f2-ffffffff820af935: tcp_retransmit_timer.cold (STB_LOCAL)
ffffffff81ecbad0-ffffffff81ecc0b7: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:477
Inline: False
```
**Symbols:**

```
ffffffff82130c7d-ffffffff82130cb2: tcp_retransmit_timer.cold (STB_LOCAL)
ffffffff81f2a650-ffffffff81f2ad75: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:506
Inline: False
```
**Symbols:**

```
ffffffff82212451-ffffffff82212486: tcp_retransmit_timer.cold (STB_LOCAL)
ffffffff81fef1d0-ffffffff81fefa25: tcp_retransmit_timer (STB_GLOBAL)
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
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffff800010c88fe8)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffff800010c88fe8-ffff800010c89910: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (c0d98054)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c0d98054-c0d98a44: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (c000000000d961e0)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c000000000d961e0-c000000000d96db0: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffe0007e9f9c)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffe0007e9f9c-ffffffe0007ea808: tcp_retransmit_timer (STB_GLOBAL)
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
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81975e40)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81975e40-ffffffff819768de: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff8192f900)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff8192f900-ffffffff8193039e: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff819e0610)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819e0610-ffffffff819e10ae: tcp_retransmit_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_retransmit_timer(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff819ea2d0)
Location: net/ipv4/tcp_timer.c:431
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819ea2d0-ffffffff819ead71: tcp_retransmit_timer (STB_GLOBAL)
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
