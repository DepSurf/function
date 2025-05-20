# Function: <code>tcp_fastopen_cache_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie, int *syn_loss, long unsigned int *last_syn_loss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff817824f0)
Location: net/ipv4/tcp_metrics.c:686
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff817824f0-ffffffff8178259d: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie, int *syn_loss, long unsigned int *last_syn_loss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff817ef9b0)
Location: net/ipv4/tcp_metrics.c:687
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff817ef9b0-ffffffff817efa5c: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie, int *syn_loss, long unsigned int *last_syn_loss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff818203c0)
Location: net/ipv4/tcp_metrics.c:686
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff818203c0-ffffffff8182046b: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie, int *syn_loss, long unsigned int *last_syn_loss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff818408e0)
Location: net/ipv4/tcp_metrics.c:551
Inline: False
```
**Symbols:**

```
ffffffff818408e0-ffffffff81840987: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie, int *syn_loss, long unsigned int *last_syn_loss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff818c0050)
Location: net/ipv4/tcp_metrics.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff818c0050-ffffffff818c00f7: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81915bd0)
Location: net/ipv4/tcp_metrics.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81915bd0-ffffffff81915c4d: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81944380)
Location: net/ipv4/tcp_metrics.c:548
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81944380-ffffffff819443fd: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819a8940)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819a8940-ffffffff819a89bc: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819df620)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819df620-ffffffff819df69c: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81acca90)
Location: net/ipv4/tcp_metrics.c:543
Inline: False
```
**Symbols:**

```
ffffffff81acca90-ffffffff81accb0e: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ad8a80)
Location: net/ipv4/tcp_metrics.c:543
Inline: False
```
**Symbols:**

```
ffffffff81ad8a80-ffffffff81ad8b05: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ac3af0)
Location: net/ipv4/tcp_metrics.c:543
Inline: False
```
**Symbols:**

```
ffffffff81ac3af0-ffffffff81ac3b73: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81b821b0)
Location: net/ipv4/tcp_metrics.c:543
Inline: False
```
**Symbols:**

```
ffffffff81b821b0-ffffffff81b82233: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81d12660)
Location: net/ipv4/tcp_metrics.c:544
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81d12660-ffffffff81d12700: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ed8470)
Location: net/ipv4/tcp_metrics.c:544
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81ed8470-ffffffff81ed8510: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81f37580)
Location: net/ipv4/tcp_metrics.c:562
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81f37580-ffffffff81f37620: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81ffd650)
Location: net/ipv4/tcp_metrics.c:561
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81ffd650-ffffffff81ffd6f0: tcp_fastopen_cache_get (STB_GLOBAL)
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
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffff800010c92f78)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffff800010c92f78-ffff800010c93038: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (c0da194c)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
c0da194c-c0da1a24: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (c000000000da32a0)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
c000000000da32a0-c000000000da338c: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffe0007f26d6)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffe0007f26d6-ffffffe0007f2778: tcp_fastopen_cache_get (STB_GLOBAL)
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
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff8197f490)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff8197f490-ffffffff8197f50c: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff81938f50)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff81938f50-ffffffff81938fcc: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819e9c60)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819e9c60-ffffffff819e9cdc: tcp_fastopen_cache_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_fastopen_cache_get(struct sock *sk, u16 *mss, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_metrics.c (ffffffff819f3a30)
Location: net/ipv4/tcp_metrics.c:538
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check
```
**Symbols:**

```
ffffffff819f3a30-ffffffff819f3ac1: tcp_fastopen_cache_get (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *syn_loss</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *last_syn_loss</code>
</li>
</ul>
</details>
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
