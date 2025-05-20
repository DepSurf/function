# Function: <code>do_tcp_sendpages</code>

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
In net/ipv4/tcp.c (ffffffff817690bc)
Location: net/ipv4/tcp.c:889
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d5a47)
Location: net/ipv4/tcp.c:878
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81805a4f)
Location: net/ipv4/tcp.c:882
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81825e40)
Location: net/ipv4/tcp.c:904
Inline: False
```
**Symbols:**

```
ffffffff81825e40-ffffffff818263c1: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a3f00)
Location: net/ipv4/tcp.c:933
Inline: False
```
**Symbols:**

```
ffffffff818a3f00-ffffffff818a449b: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f9c50)
Location: net/ipv4/tcp.c:938
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_push
```
**Symbols:**

```
ffffffff818f9c50-ffffffff818fa21c: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81927b80)
Location: net/ipv4/tcp.c:937
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81927b80-ffffffff81928141: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198aac0)
Location: net/ipv4/tcp.c:954
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff8198aac0-ffffffff8198b0b7: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c1300)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819c1300-ffffffff819c1932: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aacae0)
Location: net/ipv4/tcp.c:963
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81aacae0-ffffffff81aad134: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab5550)
Location: net/ipv4/tcp.c:1029
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81ab5550-ffffffff81ab5872: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa0740)
Location: net/ipv4/tcp.c:1028
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81aa0740-ffffffff81aa0a5f: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1025
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81d3a4b8-ffffffff81d3a4d2: do_tcp_sendpages.cold (STB_LOCAL)
ffffffff81b5c560-ffffffff81b5c8a2: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1037
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff81f06cd7-ffffffff81f06cf1: do_tcp_sendpages.cold (STB_LOCAL)
ffffffff81cea240-ffffffff81cea573: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1039
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff820ae84b-ffffffff820ae865: do_tcp_sendpages.cold (STB_LOCAL)
ffffffff81eadec0-ffffffff81eae1f3: do_tcp_sendpages (STB_GLOBAL)
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
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c74158)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffff800010c74158-ffff800010c7475c: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d827c0)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c0d827c0-c0d82df8: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7b1d0)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c000000000d7b1d0-c000000000d7b9d4: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d76e0)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffe0007d76e0-ffffffe0007d7bbc: do_tcp_sendpages (STB_GLOBAL)
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
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81961170)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81961170-ffffffff819617a2: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191ac60)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff8191ac60-ffffffff8191b292: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cb940)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819cb940-ffffffff819cbf72: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d54d0)
Location: net/ipv4/tcp.c:956
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819d54d0-ffffffff819d5b02: do_tcp_sendpages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
