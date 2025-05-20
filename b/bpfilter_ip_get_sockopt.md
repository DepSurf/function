# Function: <code>bpfilter_ip_get_sockopt</code>

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
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff8193cb70)
Location: net/ipv4/bpfilter/sockopt.c:34
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8193cb70-ffffffff8193cb9f: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff8196c9b0)
Location: net/ipv4/bpfilter/sockopt.c:60
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff8196c9b0-ffffffff8196c9df: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819d6150)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff819d6150-ffffffff819d617e: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a0cc40)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff81a0cc40-ffffffff81a0cc6e: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81afd9f0)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81afd9f0-ffffffff81afda1e: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81b0ba50)
Location: net/ipv4/bpfilter/sockopt.c:60
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81b0ba50-ffffffff81b0ba81: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81af96b0)
Location: net/ipv4/bpfilter/sockopt.c:60
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81af96b0-ffffffff81af96e1: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81bba200)
Location: net/ipv4/bpfilter/sockopt.c:60
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81bba200-ffffffff81bba231: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81d4e210)
Location: net/ipv4/bpfilter/sockopt.c:60
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81d4e210-ffffffff81d4e26b: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f17b90)
Location: net/ipv4/bpfilter/sockopt.c:60
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81f17b90-ffffffff81f17beb: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f777f0)
Location: net/ipv4/bpfilter/sockopt.c:51
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_getsockopt
```
**Symbols:**

```
ffffffff81f777f0-ffffffff81f7784b: bpfilter_ip_get_sockopt (STB_GLOBAL)
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
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffff800010cc6338)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffff800010cc6338-ffff800010cc64bc: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c0dd1ad8)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
```
**Symbols:**

```
c0dd1ad8-c0dd1b64: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c000000000de2e70)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
c000000000de2e70-c000000000de2f18: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffe00081ad66)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
```
**Symbols:**

```
ffffffe00081ad66-ffffffe00081adde: bpfilter_ip_get_sockopt (STB_GLOBAL)
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
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819ac9e0)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff819ac9e0-ffffffff819aca0e: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819664a0)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff819664a0-ffffffff819664ce: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a17280)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff81a17280-ffffffff81a172ae: bpfilter_ip_get_sockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpfilter_ip_get_sockopt(struct sock *sk, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a21cb0)
Location: net/ipv4/bpfilter/sockopt.c:58
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
```
**Symbols:**

```
ffffffff81a21cb0-ffffffff81a21cde: bpfilter_ip_get_sockopt (STB_GLOBAL)
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
