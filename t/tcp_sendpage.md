# Function: <code>tcp_sendpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81769030)
Location: net/ipv4/tcp.c:1016
Inline: True
```
**Symbols:**

```
ffffffff81769030-ffffffff8176960f: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d59a0)
Location: net/ipv4/tcp.c:1006
Inline: True
```
**Symbols:**

```
ffffffff817d59a0-ffffffff817d5fe4: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818059a0)
Location: net/ipv4/tcp.c:1013
Inline: True
```
**Symbols:**

```
ffffffff818059a0-ffffffff81805ff9: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818263d0)
Location: net/ipv4/tcp.c:1037
Inline: True
```
**Symbols:**

```
ffffffff818263d0-ffffffff81826471: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a4520)
Location: net/ipv4/tcp.c:1079
Inline: False
```
**Symbols:**

```
ffffffff818a4520-ffffffff818a457b: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fa290)
Location: net/ipv4/tcp.c:1085
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
```
**Symbols:**

```
ffffffff818fa290-ffffffff818fa2e5: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819281c0)
Location: net/ipv4/tcp.c:1084
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff819281c0-ffffffff81928215: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198b120)
Location: net/ipv4/tcp.c:1109
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff8198b120-ffffffff8198b175: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c19a0)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff819c19a0-ffffffff819c19f5: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aad1a0)
Location: net/ipv4/tcp.c:1117
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff81aad1a0-ffffffff81aad221: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab58e0)
Location: net/ipv4/tcp.c:1136
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff81ab58e0-ffffffff81ab5961: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa0ac0)
Location: net/ipv4/tcp.c:1135
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff81aa0ac0-ffffffff81aa0b41: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5c910)
Location: net/ipv4/tcp.c:1132
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff81b5c910-ffffffff81b5c991: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cea600)
Location: net/ipv4/tcp.c:1144
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff81cea600-ffffffff81cea68e: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eae2a0)
Location: net/ipv4/tcp.c:1146
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff81eae2a0-ffffffff81eae32e: tcp_sendpage (STB_GLOBAL)
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
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c747f8)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffff800010c747f8-ffff800010c74870: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d82e6c)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
c0d82e6c-c0d82ed0: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7baa0)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
c000000000d7baa0-c000000000d7bb2c: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d7c30)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffe0007d7c30-ffffffe0007d7c94: tcp_sendpage (STB_GLOBAL)
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
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81961810)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff81961810-ffffffff81961865: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191b300)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff8191b300-ffffffff8191b355: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cbfe0)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff819cbfe0-ffffffff819cc035: tcp_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_sendpage(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d5b70)
Location: net/ipv4/tcp.c:1110
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
**Symbols:**

```
ffffffff819d5b70-ffffffff819d5bc5: tcp_sendpage (STB_GLOBAL)
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
