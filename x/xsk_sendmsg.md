# Function: <code>xsk_sendmsg</code>

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
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cc0b0)
Location: net/xdp/xsk.c:279
Inline: False
```
**Symbols:**

```
ffffffff819cc0b0-ffffffff819cc3ad: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a05290)
Location: net/xdp/xsk.c:291
Inline: False
```
**Symbols:**

```
ffffffff81a05290-ffffffff81a0558c: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a748f0)
Location: net/xdp/xsk.c:298
Inline: False
```
**Symbols:**

```
ffffffff81a748f0-ffffffff81a74c24: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaa710)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
ffffffff81aaa710-ffffffff81aaa747: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7b70)
Location: net/xdp/xsk.c:410
Inline: False
```
**Symbols:**

```
ffffffff81ba7b70-ffffffff81ba7ba7: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7660)
Location: net/xdp/xsk.c:544
Inline: False
```
**Symbols:**

```
ffffffff81bb7660-ffffffff81bb77b2: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6830)
Location: net/xdp/xsk.c:637
Inline: False
```
**Symbols:**

```
ffffffff81ba6830-ffffffff81ba693c: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c744a0)
Location: net/xdp/xsk.c:637
Inline: False
```
**Symbols:**

```
ffffffff81c744a0-ffffffff81c745ac: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:654
Inline: False
```
**Symbols:**

```
ffffffff81e185d0-ffffffff81e1871b: xsk_sendmsg (STB_LOCAL)
ffffffff81f0fa8f-ffffffff81f0faa4: xsk_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fef7a0)
Location: net/xdp/xsk.c:665
Inline: False
```
**Symbols:**

```
ffffffff81fef7a0-ffffffff81fef7db: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206b760)
Location: net/xdp/xsk.c:666
Inline: False
```
**Symbols:**

```
ffffffff8206b760-ffffffff8206b79b: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213f4f0)
Location: net/xdp/xsk.c:939
Inline: False
```
**Symbols:**

```
ffffffff8213f4f0-ffffffff8213f52b: xsk_sendmsg (STB_LOCAL)
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
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7e3b8)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
ffff800010d7e3b8-ffff800010d7e41c: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e799d8)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
c0e799d8-c0e79a28: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebeeb0)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
c000000000ebeeb0-c000000000ebef08: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ac79e)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
ffffffe0008ac79e-ffffffe0008ac7fe: xsk_sendmsg (STB_LOCAL)
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
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a49aa0)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
ffffffff81a49aa0-ffffffff81a49ad7: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a06690)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
ffffffff81a06690-ffffffff81a066c7: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab5950)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
ffffffff81ab5950-ffffffff81ab5987: xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xsk_sendmsg(struct socket *sock, struct msghdr *m, size_t total_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac3050)
Location: net/xdp/xsk.c:416
Inline: False
```
**Symbols:**

```
ffffffff81ac3050-ffffffff81ac3087: xsk_sendmsg (STB_LOCAL)
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
