# Function: <code>bpfilter_ip_set_sockopt</code>

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
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff8193cb50)
Location: net/ipv4/bpfilter/sockopt.c:28
Inline: False
```
**Symbols:**

```
ffffffff8193cb50-ffffffff8193cb66: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff8196c990)
Location: net/ipv4/bpfilter/sockopt.c:54
Inline: False
```
**Symbols:**

```
ffffffff8196c990-ffffffff8196c9a6: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819d6130)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffffffff819d6130-ffffffff819d6146: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a0cc20)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81a0cc20-ffffffff81a0cc36: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81afd9d0)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_setsockopt
```
**Symbols:**

```
ffffffff81afd9d0-ffffffff81afd9e6: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81b0ba30)
Location: net/ipv4/bpfilter/sockopt.c:54
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_setsockopt
```
**Symbols:**

```
ffffffff81b0ba30-ffffffff81b0ba46: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81af9690)
Location: net/ipv4/bpfilter/sockopt.c:54
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_setsockopt
```
**Symbols:**

```
ffffffff81af9690-ffffffff81af96a6: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81bba1e0)
Location: net/ipv4/bpfilter/sockopt.c:54
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_setsockopt
```
**Symbols:**

```
ffffffff81bba1e0-ffffffff81bba1f6: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81d4e1e0)
Location: net/ipv4/bpfilter/sockopt.c:54
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_setsockopt
```
**Symbols:**

```
ffffffff81d4e1e0-ffffffff81d4e208: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f17b50)
Location: net/ipv4/bpfilter/sockopt.c:54
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_setsockopt
```
**Symbols:**

```
ffffffff81f17b50-ffffffff81f17b78: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f777b0)
Location: net/ipv4/bpfilter/sockopt.c:45
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_setsockopt
```
**Symbols:**

```
ffffffff81f777b0-ffffffff81f777d8: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
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
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffff800010cc62e8)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffff800010cc62e8-ffff800010cc6338: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c0dd1aac)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
c0dd1aac-c0dd1ad8: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c000000000de2e50)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
c000000000de2e50-c000000000de2e68: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffe00081ad22)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffffffe00081ad22-ffffffe00081ad66: bpfilter_ip_set_sockopt (STB_GLOBAL)
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
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819ac9c0)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffffffff819ac9c0-ffffffff819ac9d6: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81966480)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81966480-ffffffff81966496: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a17260)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81a17260-ffffffff81a17276: bpfilter_ip_set_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpfilter_ip_set_sockopt(struct sock *sk, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a21c90)
Location: net/ipv4/bpfilter/sockopt.c:52
Inline: False
```
**Symbols:**

```
ffffffff81a21c90-ffffffff81a21ca6: bpfilter_ip_set_sockopt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
