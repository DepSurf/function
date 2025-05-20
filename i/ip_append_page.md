# Function: <code>ip_append_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175eb20)
Location: net/ipv4/ip_output.c:1192
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff8175eb20-ffffffff8175f021: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817cadd0)
Location: net/ipv4/ip_output.c:1190
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff817cadd0-ffffffff817cb29c: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817faa30)
Location: net/ipv4/ip_output.c:1231
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff817faa30-ffffffff817faef1: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181ae30)
Location: net/ipv4/ip_output.c:1243
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff8181ae30-ffffffff8181b2e1: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81899e10)
Location: net/ipv4/ip_output.c:1175
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81899e10-ffffffff8189a21a: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818ee2a0)
Location: net/ipv4/ip_output.c:1199
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff818ee2a0-ffffffff818ee6ec: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191ba70)
Location: net/ipv4/ip_output.c:1225
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff8191ba70-ffffffff8191bea0: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197dd50)
Location: net/ipv4/ip_output.c:1314
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff8197dd50-ffffffff8197e1aa: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b46f0)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff819b46f0-ffffffff819b4b5a: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9e8a0)
Location: net/ipv4/ip_output.c:1321
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81a9e8a0-ffffffff81a9ed3a: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa87f0)
Location: net/ipv4/ip_output.c:1328
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81aa87f0-ffffffff81aa8c75: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a93910)
Location: net/ipv4/ip_output.c:1332
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81a93910-ffffffff81a93d91: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4ed50)
Location: net/ipv4/ip_output.c:1331
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81b4ed50-ffffffff81b4f1da: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdc690)
Location: net/ipv4/ip_output.c:1331
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81cdc690-ffffffff81cdcb67: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9d0f0)
Location: net/ipv4/ip_output.c:1348
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81e9d0f0-ffffffff81e9d5c7: ip_append_page (STB_GLOBAL)
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
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c64eb0)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffff800010c64eb0-ffff800010c652ec: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d74acc)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
c0d74acc-c0d74f2c: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d691f0)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
c000000000d691f0-c000000000d69824: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007cc79c)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffe0007cc79c-ffffffe0007ccb42: ip_append_page (STB_GLOBAL)
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
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81954560)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff81954560-ffffffff819549ca: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190e050)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff8190e050-ffffffff8190e4ba: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bed30)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff819bed30-ffffffff819bf19a: ip_append_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ip_append_page(struct sock *sk, struct flowi4 *fl4, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c86b0)
Location: net/ipv4/ip_output.c:1322
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
```
**Symbols:**

```
ffffffff819c86b0-ffffffff819c8b13: ip_append_page (STB_GLOBAL)
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
