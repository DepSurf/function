# Function: <code>tcp_bpf_sendpage</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81977690)
Location: net/ipv4/tcp_bpf.c:479
Inline: False
```
**Symbols:**

```
ffffffff81977690-ffffffff81977909: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819e11c0)
Location: net/ipv4/tcp_bpf.c:486
Inline: False
```
**Symbols:**

```
ffffffff819e11c0-ffffffff819e1420: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a18580)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
ffffffff81a18580-ffffffff81a187cc: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b09280)
Location: net/ipv4/tcp_bpf.c:492
Inline: False
```
**Symbols:**

```
ffffffff81b09280-ffffffff81b094f8: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b17a90)
Location: net/ipv4/tcp_bpf.c:496
Inline: False
```
**Symbols:**

```
ffffffff81b17a90-ffffffff81b17d0a: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b05660)
Location: net/ipv4/tcp_bpf.c:394
Inline: False
```
**Symbols:**

```
ffffffff81b05660-ffffffff81b058e4: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc81b0)
Location: net/ipv4/tcp_bpf.c:472
Inline: False
```
**Symbols:**

```
ffffffff81bc81b0-ffffffff81bc847f: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5da10)
Location: net/ipv4/tcp_bpf.c:473
Inline: False
```
**Symbols:**

```
ffffffff81d5da10-ffffffff81d5dd59: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f276c0)
Location: net/ipv4/tcp_bpf.c:481
Inline: False
```
**Symbols:**

```
ffffffff81f276c0-ffffffff81f27a09: tcp_bpf_sendpage (STB_LOCAL)
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
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffff800010cd3d50)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
ffff800010cd3d50-ffff800010cd3fb0: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c0dddc4c)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
c0dddc4c-c0dddea0: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c000000000df30f0)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
c000000000df30f0-c000000000df3464: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffe000824be2)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
ffffffe000824be2-ffffffe000824ddc: tcp_bpf_sendpage (STB_LOCAL)
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
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819b7c10)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
ffffffff819b7c10-ffffffff819b7e5c: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81974a00)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
ffffffff81974a00-ffffffff81974c4c: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a22690)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
ffffffff81a22690-ffffffff81a228dc: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_bpf_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a2da30)
Location: net/ipv4/tcp_bpf.c:483
Inline: False
```
**Symbols:**

```
ffffffff81a2da30-ffffffff81a2dc8d: tcp_bpf_sendpage (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
