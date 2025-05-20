# Function: <code>inet_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81794da0)
Location: net/ipv4/af_inet.c:725
Inline: False
```
**Symbols:**

```
ffffffff81794da0-ffffffff81794e35: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81802780)
Location: net/ipv4/af_inet.c:729
Inline: False
```
**Symbols:**

```
ffffffff81802780-ffffffff81802815: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81833720)
Location: net/ipv4/af_inet.c:733
Inline: False
```
**Symbols:**

```
ffffffff81833720-ffffffff818337c4: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81854480)
Location: net/ipv4/af_inet.c:751
Inline: False
```
**Symbols:**

```
ffffffff81854480-ffffffff81854524: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d4310)
Location: net/ipv4/af_inet.c:752
Inline: False
```
**Symbols:**

```
ffffffff818d4310-ffffffff818d43bd: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8192a7c0)
Location: net/ipv4/af_inet.c:787
Inline: False
```
**Symbols:**

```
ffffffff8192a7c0-ffffffff8192a86a: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8195a0b0)
Location: net/ipv4/af_inet.c:787
Inline: False
```
**Symbols:**

```
ffffffff8195a0b0-ffffffff8195a15a: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bea80)
Location: net/ipv4/af_inet.c:800
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff819bea80-ffffffff819beaee: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f56b0)
Location: net/ipv4/af_inet.c:800
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff819f56b0-ffffffff819f571e: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae3d40)
Location: net/ipv4/af_inet.c:807
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81ae3d40-ffffffff81ae3dae: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af0c70)
Location: net/ipv4/af_inet.c:810
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81af0c70-ffffffff81af0cde: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adc430)
Location: net/ipv4/af_inet.c:814
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81adc430-ffffffff81adc49e: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b9b880)
Location: net/ipv4/af_inet.c:816
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81b9b880-ffffffff81b9b8ee: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2d710)
Location: net/ipv4/af_inet.c:812
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81d2d710-ffffffff81d2d78f: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef55f0)
Location: net/ipv4/af_inet.c:821
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81ef55f0-ffffffff81ef566f: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f54ea0)
Location: net/ipv4/af_inet.c:823
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81f54ea0-ffffffff81f54f1f: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201b110)
Location: net/ipv4/af_inet.c:843
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff8201b110-ffffffff8201b18f: inet_sendmsg (STB_GLOBAL)
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
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cac570)
Location: net/ipv4/af_inet.c:800
Inline: False
```
**Symbols:**

```
ffff800010cac570-ffff800010cac5e0: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db8188)
Location: net/ipv4/af_inet.c:800
Inline: False
```
**Symbols:**

```
c0db8188-c0db81dc: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc1a40)
Location: net/ipv4/af_inet.c:800
Inline: False
```
**Symbols:**

```
c000000000dc1a40-c000000000dc1af0: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe000806074)
Location: net/ipv4/af_inet.c:800
Inline: False
```
**Symbols:**

```
ffffffe000806074-ffffffe0008060ca: inet_sendmsg (STB_GLOBAL)
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
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81995450)
Location: net/ipv4/af_inet.c:800
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81995450-ffffffff819954be: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194ef10)
Location: net/ipv4/af_inet.c:800
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff8194ef10-ffffffff8194ef7e: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819ffcf0)
Location: net/ipv4/af_inet.c:800
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff819ffcf0-ffffffff819ffd5e: inet_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet_sendmsg(struct socket *sock, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a09e20)
Location: net/ipv4/af_inet.c:800
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_sendmsg
```
**Symbols:**

```
ffffffff81a09e20-ffffffff81a09e8e: inet_sendmsg (STB_GLOBAL)
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
