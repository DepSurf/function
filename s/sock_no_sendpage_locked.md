# Function: <code>sock_no_sendpage_locked</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182ac80)
Location: net/core/sock.c:2574
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff8182ac80-ffffffff8182ad2c: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874d70)
Location: net/core/sock.c:2649
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff81874d70-ffffffff81874e19: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895630)
Location: net/core/sock.c:2593
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff81895630-ffffffff818956d9: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818dfb50)
Location: net/core/sock.c:2736
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff818dfb50-ffffffff818dfbfc: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911d00)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff81911d00-ffffffff81911dac: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3c50)
Location: net/core/sock.c:2880
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff819e3c50-ffffffff819e3d02: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e35e0)
Location: net/core/sock.c:2852
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff819e35e0-ffffffff819e3692: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c9660)
Location: net/core/sock.c:2875
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff819c9660-ffffffff819c9712: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a789e0)
Location: net/core/sock.c:3006
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81a789e0-ffffffff81a78a92: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bec430)
Location: net/core/sock.c:3169
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81bec430-ffffffff81bec501: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d98eb0)
Location: net/core/sock.c:3249
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81d98eb0-ffffffff81d98f87: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010ba97c8)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffff800010ba97c8-ffff800010ba988c: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc7d9c)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
c0cc7d9c-c0cc7e58: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7ecf0)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
c000000000c7ecf0-c000000000c7ede4: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073cd44)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffe00073cd44-ffffffe00073cdea: sock_no_sendpage_locked (STB_GLOBAL)
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
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1d00)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff818b1d00-ffffffff818b1dac: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186bc50)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff8186bc50-ffffffff8186bcfc: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902d00)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff81902d00-ffffffff81902dac: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t sock_no_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81923c90)
Location: net/core/sock.c:2751
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage_locked
```
**Symbols:**

```
ffffffff81923c90-ffffffff81923d16: sock_no_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
