# Function: <code>inet_twsk_hashdance</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3370)
Location: net/ipv4/inet_timewait_sock.c:100
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff818f3370-ffffffff818f3489: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81920e90)
Location: net/ipv4/inet_timewait_sock.c:100
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81920e90-ffffffff81920fa9: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (0)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81983cce-ffffffff81983ce8: inet_twsk_hashdance.cold (STB_LOCAL)
ffffffff81983860-ffffffff81983971: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba050)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff819ba050-ffffffff819ba16a: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4ae0)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81aa4ae0-ffffffff81aa4bfa: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf140)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81aaf140-ffffffff81aaf25a: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a450)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81a9a450-ffffffff81a9a56d: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81b558c0)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81b558c0-ffffffff81b559dd: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce32c0)
Location: net/ipv4/inet_timewait_sock.c:103
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81ce32c0-ffffffff81ce33ef: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5b30)
Location: net/ipv4/inet_timewait_sock.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81ea5b30-ffffffff81ea5e55: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81f042b0)
Location: net/ipv4/inet_timewait_sock.c:114
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81f042b0-ffffffff81f04606: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8600)
Location: net/ipv4/inet_timewait_sock.c:100
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81fc8600-ffffffff81fc892c: inet_twsk_hashdance (STB_GLOBAL)
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
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffff800010c6ba18)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffff800010c6ba18-ffff800010c6bbc4: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c0d7a748)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
c0d7a748-c0d7a8b8: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c000000000d70cf0)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
c000000000d70cf0-c000000000d70f00: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d144a)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffe0007d144a-ffffffe0007d15c4: inet_twsk_hashdance (STB_GLOBAL)
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
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81959ec0)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff81959ec0-ffffffff81959fda: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819139b0)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff819139b0-ffffffff81913aca: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4690)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff819c4690-ffffffff819c47aa: inet_twsk_hashdance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_twsk_hashdance(struct inet_timewait_sock *tw, struct sock *sk, struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819cdf50)
Location: net/ipv4/inet_timewait_sock.c:101
Inline: False
Direct callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
**Symbols:**

```
ffffffff819cdf50-ffffffff819ce066: inet_twsk_hashdance (STB_GLOBAL)
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
