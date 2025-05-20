# Function: <code>inet_csk_destroy_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81764900)
Location: net/ipv4/inet_connection_sock.c:695
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81764900-ffffffff81764a39: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d0e40)
Location: net/ipv4/inet_connection_sock.c:691
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff817d0e40-ffffffff817d0fa4: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81800d00)
Location: net/ipv4/inet_connection_sock.c:695
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81800d00-ffffffff81800e64: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820ad0)
Location: net/ipv4/inet_connection_sock.c:822
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81820ad0-ffffffff81820bcd: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189fab0)
Location: net/ipv4/inet_connection_sock.c:820
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8189fab0-ffffffff8189fbb9: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f4b20)
Location: net/ipv4/inet_connection_sock.c:815
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818f4b20-ffffffff818f4c12: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81922020)
Location: net/ipv4/inet_connection_sock.c:834
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81922020-ffffffff81922112: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:825
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81985f25-ffffffff81985f71: inet_csk_destroy_sock.cold (STB_LOCAL)
ffffffff81985110-ffffffff819851f9: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bb1c0)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819bb1c0-ffffffff819bb2e3: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa60a0)
Location: net/ipv4/inet_connection_sock.c:879
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81aa60a0-ffffffff81aa61ee: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab06f0)
Location: net/ipv4/inet_connection_sock.c:876
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81ab06f0-ffffffff81ab083e: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b8d0)
Location: net/ipv4/inet_connection_sock.c:876
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81a9b8d0-ffffffff81a9ba1e: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b56f00)
Location: net/ipv4/inet_connection_sock.c:999
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81b56f00-ffffffff81b57034: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4e60)
Location: net/ipv4/inet_connection_sock.c:1001
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81ce4e60-ffffffff81ce4fac: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7aa0)
Location: net/ipv4/inet_connection_sock.c:1164
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81ea7aa0-ffffffff81ea7bec: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f062e0)
Location: net/ipv4/inet_connection_sock.c:1188
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81f062e0-ffffffff81f0642c: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fca5d0)
Location: net/ipv4/inet_connection_sock.c:1188
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81fca5d0-ffffffff81fca71c: inet_csk_destroy_sock (STB_GLOBAL)
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
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6c790)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffff800010c6c790-ffff800010c6c8b8: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7bc78)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c0d7bc78-c0d7bdec: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d72a00)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c000000000d72a00-c000000000d72bb0: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d20ba)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffe0007d20ba-ffffffe0007d2190: inet_csk_destroy_sock (STB_GLOBAL)
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
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195b030)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8195b030-ffffffff8195b153: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81914b20)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81914b20-ffffffff81914c43: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c5800)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819c5800-ffffffff819c5923: inet_csk_destroy_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_csk_destroy_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cf2e0)
Location: net/ipv4/inet_connection_sock.c:845
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819cf2e0-ffffffff819cf403: inet_csk_destroy_sock (STB_GLOBAL)
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
