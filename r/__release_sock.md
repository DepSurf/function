# Function: <code>__release_sock</code>

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
In net/core/sock.c (ffffffff81702230)
Location: net/core/sock.c:1993
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81769410)
Location: net/core/sock.c:2050
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
```
**Symbols:**

```
ffffffff81769410-ffffffff817694fa: __release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81796320)
Location: net/core/sock.c:2048
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
```
**Symbols:**

```
ffffffff81796320-ffffffff8179640a: __release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4500)
Location: net/core/sock.c:2207
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
```
**Symbols:**

```
ffffffff817b4500-ffffffff817b45cf: __release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182c750)
Location: net/core/sock.c:2245
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
```
**Symbols:**

```
ffffffff8182c750-ffffffff8182c824: __release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818768c0)
Location: net/core/sock.c:2326
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
```
**Symbols:**

```
ffffffff818768c0-ffffffff81876990: __release_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81898750)
Location: net/core/sock.c:2268
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81898750-ffffffff8189881d: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e2d00)
Location: net/core/sock.c:2411
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818e2d00-ffffffff818e2dbd: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914ee0)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81914ee0-ffffffff81914f9d: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8000)
Location: net/core/sock.c:2534
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819e8000-ffffffff819e80bd: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e7c70)
Location: net/core/sock.c:2526
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff819e7c70-ffffffff819e7d2d: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cdc40)
Location: net/core/sock.c:2549
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff819cdc40-ffffffff819cdcfd: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7d420)
Location: net/core/sock.c:2672
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81a7d420-ffffffff81a7d4da: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf0a80)
Location: net/core/sock.c:2835
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81bf0a80-ffffffff81bf0b60: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9d100)
Location: net/core/sock.c:2914
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81d9d100-ffffffff81d9d1d0: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0b950)
Location: net/core/sock.c:2975
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81e0b950-ffffffff81e0ba20: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec8340)
Location: net/core/sock.c:2956
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81ec8340-ffffffff81ec8410: __release_sock (STB_GLOBAL)
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
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010badcc8)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffff800010badcc8-ffff800010badddc: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccb7cc)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c0ccb7cc-c0ccb8d4: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c836a0)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c000000000c836a0-c000000000c837c8: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073fdca)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffe00073fdca-ffffffe00073fe76: __release_sock (STB_GLOBAL)
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
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4ee0)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818b4ee0-ffffffff818b4f9d: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ee30)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8186ee30-ffffffff8186eeed: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905ee0)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81905ee0-ffffffff81905f9d: __release_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __release_sock(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926f10)
Location: net/core/sock.c:2426
Inline: False
Direct callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81926f10-ffffffff81926fc8: __release_sock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
