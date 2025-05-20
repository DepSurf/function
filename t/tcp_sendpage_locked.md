# Function: <code>tcp_sendpage_locked</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a44a0)
Location: net/ipv4/tcp.c:1066
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff818a44a0-ffffffff818a451e: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fa220)
Location: net/ipv4/tcp.c:1073
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff818fa220-ffffffff818fa286: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81928150)
Location: net/ipv4/tcp.c:1072
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81928150-ffffffff819281b6: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198b0c0)
Location: net/ipv4/tcp.c:1097
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff8198b0c0-ffffffff8198b11e: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c1940)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff819c1940-ffffffff819c199e: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aad1c8)
Location: net/ipv4/tcp.c:1105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81aad140-ffffffff81aad19e: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab5908)
Location: net/ipv4/tcp.c:1124
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81ab5880-ffffffff81ab58de: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa0ae8)
Location: net/ipv4/tcp.c:1123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81aa0a60-ffffffff81aa0abe: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5c938)
Location: net/ipv4/tcp.c:1120
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81b5c8b0-ffffffff81b5c90e: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cea628)
Location: net/ipv4/tcp.c:1132
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81cea580-ffffffff81cea5fc: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eae2c8)
Location: net/ipv4/tcp.c:1134
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendpage
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff81eae210-ffffffff81eae28c: tcp_sendpage_locked (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c74760)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffff800010c74760-ffff800010c747f8: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d82df8)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
c0d82df8-c0d82e6c: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7b9e0)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
c000000000d7b9e0-c000000000d7ba9c: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d7bbc)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffe0007d7bbc-ffffffe0007d7c30: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819617b0)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff819617b0-ffffffff8196180e: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191b2a0)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff8191b2a0-ffffffff8191b2fe: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cbf80)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff819cbf80-ffffffff819cbfde: tcp_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcp_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d5b10)
Location: net/ipv4/tcp.c:1098
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendpage
```
**Symbols:**

```
ffffffff819d5b10-ffffffff819d5b6e: tcp_sendpage_locked (STB_GLOBAL)
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
