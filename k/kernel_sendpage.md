# Function: <code>kernel_sendpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fda60)
Location: net/socket.c:3269
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff816fda60-ffffffff816fda84: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764590)
Location: net/socket.c:3271
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff81764590-ffffffff817645b4: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817915d0)
Location: net/socket.c:3319
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff817915d0-ffffffff817915f4: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817af100)
Location: net/socket.c:3369
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff817af100-ffffffff817af124: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81827210)
Location: net/socket.c:3371
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff81827210-ffffffff81827237: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818705b0)
Location: net/socket.c:3335
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff818705b0-ffffffff818705d7: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81891180)
Location: net/socket.c:3401
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff81891180-ffffffff818911a7: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dae70)
Location: net/socket.c:3678
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff818dae70-ffffffff818dae97: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190cfc0)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff8190cfc0-ffffffff8190cfe7: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df99d)
Location: net/socket.c:3638
Inline: True
Inline callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff819ded30-ffffffff819ded57: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819dedf6)
Location: net/socket.c:3630
Inline: True
Inline callers:
  - net/socket.c:sock_sendpage
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff819de920-ffffffff819de9b9: kernel_sendpage.part.0 (STB_LOCAL)
ffffffff819de9c0-ffffffff819de9e5: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c48c0)
Location: net/socket.c:3616
Inline: True
Direct callers:
  - net/socket.c:sock_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff819c48c0-ffffffff819c4972: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81a73d48)
Location: net/socket.c:3501
Inline: True
Direct callers:
  - net/socket.c:sock_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81d34a27-ffffffff81d34a51: kernel_sendpage.cold (STB_LOCAL)
ffffffff81a73d20-ffffffff81a73dfb: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81be77e8)
Location: net/socket.c:3561
Inline: True
Direct callers:
  - net/socket.c:sock_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81f00f40-ffffffff81f00f6b: kernel_sendpage.cold (STB_LOCAL)
ffffffff81be77c0-ffffffff81be7926: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81d93ff8)
Location: net/socket.c:3549
Inline: True
Direct callers:
  - net/socket.c:sock_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff820aab16-ffffffff820aab41: kernel_sendpage.cold (STB_LOCAL)
ffffffff81d93fd0-ffffffff81d94136: kernel_sendpage (STB_GLOBAL)
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
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1df0)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffff800010ba1df0-ffff800010ba1e70: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3ec4)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
c0cc3ec4-c0cc3f0c: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76b20)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
c000000000c76b20-c000000000c76b8c: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739f6a)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffe000739f6a-ffffffe000739fc2: kernel_sendpage (STB_GLOBAL)
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
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818acfc0)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff818acfc0-ffffffff818acfe7: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866f10)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff81866f10-ffffffff81866f37: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fdfc0)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff818fdfc0-ffffffff818fdfe7: kernel_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191f050)
Location: net/socket.c:3759
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
```
**Symbols:**

```
ffffffff8191f050-ffffffff8191f077: kernel_sendpage (STB_GLOBAL)
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
