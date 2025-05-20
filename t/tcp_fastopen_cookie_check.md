# Function: <code>tcp_fastopen_cookie_check</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff818413e0)
Location: net/ipv4/tcp_fastopen.c:331
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff818413e0-ffffffff818414c4: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff818c0c00)
Location: net/ipv4/tcp_fastopen.c:379
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff818c0c00-ffffffff818c0cff: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81916730)
Location: net/ipv4/tcp_fastopen.c:379
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81916730-ffffffff819167ce: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81944ed0)
Location: net/ipv4/tcp_fastopen.c:379
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81944ed0-ffffffff81944f69: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a9500)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff819a9500-ffffffff819a9597: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819e01a0)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff819e01a0-ffffffff819e0253: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81acd790)
Location: net/ipv4/tcp_fastopen.c:429
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81acd790-ffffffff81acd845: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad97d0)
Location: net/ipv4/tcp_fastopen.c:429
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81ad97d0-ffffffff81ad9885: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac48e0)
Location: net/ipv4/tcp_fastopen.c:429
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81ac48e0-ffffffff81ac495d: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81b83030)
Location: net/ipv4/tcp_fastopen.c:417
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81b83030-ffffffff81b830c1: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81d13610)
Location: net/ipv4/tcp_fastopen.c:411
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81d13610-ffffffff81d136b5: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ed95b0)
Location: net/ipv4/tcp_fastopen.c:412
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81ed95b0-ffffffff81ed9655: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81f38690)
Location: net/ipv4/tcp_fastopen.c:414
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81f38690-ffffffff81f38735: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe750)
Location: net/ipv4/tcp_fastopen.c:414
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81ffe750-ffffffff81ffe7f5: tcp_fastopen_cookie_check (STB_GLOBAL)
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
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffff800010c93d70)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffff800010c93d70-ffff800010c93e70: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c0da25ec)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
c0da25ec-c0da26a8: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c000000000da4340)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
c000000000da4340-c000000000da4490: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffe0007f333c)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffe0007f333c-ffffffe0007f3432: tcp_fastopen_cookie_check (STB_GLOBAL)
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
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81980010)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81980010-ffffffff819800c3: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81939ad0)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff81939ad0-ffffffff81939b83: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819ea7e0)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff819ea7e0-ffffffff819ea893: tcp_fastopen_cookie_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819f4650)
Location: net/ipv4/tcp_fastopen.c:406
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
```
**Symbols:**

```
ffffffff819f4650-ffffffff819f4703: tcp_fastopen_cookie_check (STB_GLOBAL)
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
