# Function: <code>move_addr_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fcba0)
Location: net/socket.c:216
Inline: False
Direct callers:
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff816fcba0-ffffffff816fcc69: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817638a0)
Location: net/socket.c:216
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_accept4
```
**Symbols:**

```
ffffffff817638a0-ffffffff81763975: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790890)
Location: net/socket.c:216
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_accept4
```
**Symbols:**

```
ffffffff81790890-ffffffff81790965: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817adf00)
Location: net/socket.c:216
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_accept4
```
**Symbols:**

```
ffffffff817adf00-ffffffff817adfd5: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825f60)
Location: net/socket.c:216
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_accept4
```
**Symbols:**

```
ffffffff81825f60-ffffffff81826035: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f840)
Location: net/socket.c:210
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff8186f840-ffffffff8186f915: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818903f0)
Location: net/socket.c:210
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff818903f0-ffffffff818904fc: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da280)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff818da280-ffffffff818da37b: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c260)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff8190c260-ffffffff8190c35b: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de4c0)
Location: net/socket.c:220
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff819de4c0-ffffffff819de5b8: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819ddf20)
Location: net/socket.c:220
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff819ddf20-ffffffff819ddff6: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c3f30)
Location: net/socket.c:220
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4_file
```
**Symbols:**

```
ffffffff819c3f30-ffffffff819c4006: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73540)
Location: net/socket.c:270
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:do_accept
```
**Symbols:**

```
ffffffff81a73540-ffffffff81a73616: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be60c0)
Location: net/socket.c:271
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:do_accept
```
**Symbols:**

```
ffffffff81be60c0-ffffffff81be6193: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d92320)
Location: net/socket.c:271
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:do_accept
```
**Symbols:**

```
ffffffff81d92320-ffffffff81d923f3: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e006e0)
Location: net/socket.c:273
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:do_accept
```
**Symbols:**

```
ffffffff81e006e0-ffffffff81e007b3: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebcc40)
Location: net/socket.c:275
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:do_accept
```
**Symbols:**

```
ffffffff81ebcc40-ffffffff81ebcd13: move_addr_to_user (STB_LOCAL)
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
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba4480)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffff800010ba4480-ffff800010ba4768: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc4a30)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
c0cc4a30-c0cc4bc4: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c77da0)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
c000000000c77da0-c000000000c77fe4: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe0007393bc)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffe0007393bc-ffffffe000739498: move_addr_to_user (STB_LOCAL)
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
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac260)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff818ac260-ffffffff818ac35b: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818661b0)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff818661b0-ffffffff818662ab: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd260)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff818fd260-ffffffff818fd35b: move_addr_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int move_addr_to_user(struct __kernel_sockaddr_storage *kaddr, int klen, void *uaddr, int *ulen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e2d0)
Location: net/socket.c:206
Inline: False
Direct callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_accept4
```
**Symbols:**

```
ffffffff8191e2d0-ffffffff8191e3cb: move_addr_to_user (STB_LOCAL)
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
