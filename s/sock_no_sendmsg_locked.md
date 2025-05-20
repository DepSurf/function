# Function: <code>sock_no_sendmsg_locked</code>

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
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2540
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff8182c5b0-ffffffff8182c5c0: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2615
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff81876790-ffffffff818767a0: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2559
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff81897020-ffffffff81897030: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df3f0)
Location: net/core/sock.c:2702
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff818df3f0-ffffffff818df400: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819115c0)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff819115c0-ffffffff819115d0: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2825
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff819e49e0-ffffffff819e49f0: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2803
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff819e4200-ffffffff819e4210: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2826
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff819ca290-ffffffff819ca2a0: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2957
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff81a79830-ffffffff81a79840: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3120
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff81bed1c0-ffffffff81bed1d4: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3200
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff81d99460-ffffffff81d99474: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3261
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
  - net/core/skbuff.c:sendmsg_locked
```
**Symbols:**

```
ffffffff81e07780-ffffffff81e07794: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3271
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
  - net/core/skbuff.c:sendmsg_locked
```
**Symbols:**

```
ffffffff81ec40d0-ffffffff81ec40e4: sock_no_sendmsg_locked (STB_GLOBAL)
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
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffff800010baa8c0-ffff800010baa8dc: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
c0cc9788-c0cc97a4: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e000)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
c000000000c7e000-c000000000c7e010: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffe00073e4ee-ffffffe00073e50c: sock_no_sendmsg_locked (STB_GLOBAL)
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
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b15c0)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff818b15c0-ffffffff818b15d0: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b510)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff8186b510-ffffffff8186b520: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819025c0)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff819025c0-ffffffff819025d0: sock_no_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock *sk, struct msghdr *m, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81923560)
Location: net/core/sock.c:2717
Inline: False
Direct callers:
  - net/socket.c:kernel_sendmsg_locked
```
**Symbols:**

```
ffffffff81923560-ffffffff81923570: sock_no_sendmsg_locked (STB_GLOBAL)
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
