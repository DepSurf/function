# Function: <code>__inet6_bind</code>

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
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff8195e970)
Location: net/ipv6/af_inet6.c:276
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff8195e970-ffffffff8195ef09: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819934d0)
Location: net/ipv6/af_inet6.c:277
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff819934d0-ffffffff81993afe: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819fef70)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff819fef70-ffffffff819ff5a9: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a35b70)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81a35b70-ffffffff81a361a9: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b2ac30)
Location: net/ipv6/af_inet6.c:277
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81b2ac30-ffffffff81b2b26a: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b395c0)
Location: net/ipv6/af_inet6.c:277
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81b395c0-ffffffff81b39c97: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b27290)
Location: net/ipv6/af_inet6.c:277
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81b27290-ffffffff81b27977: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:278
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81bed1c0-ffffffff81bed8b2: __inet6_bind (STB_LOCAL)
ffffffff81d3f189-ffffffff81d3f1cd: __inet6_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:279
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81d856b0-ffffffff81d85d95: __inet6_bind (STB_LOCAL)
ffffffff81f0bac6-ffffffff81f0bb1a: __inet6_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:287
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81f53170-ffffffff81f53851: __inet6_bind (STB_LOCAL)
ffffffff820b32c6-ffffffff820b331a: __inet6_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:277
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81fb2be0-ffffffff81fb3243: __inet6_bind (STB_LOCAL)
ffffffff821344b6-ffffffff821344cf: __inet6_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/af_inet6.c (0)
Location: net/ipv6/af_inet6.c:281
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind_sk
```
**Symbols:**

```
ffffffff820803c0-ffffffff82080a5c: __inet6_bind (STB_LOCAL)
ffffffff8221607f-ffffffff82216098: __inet6_bind.cold (STB_LOCAL)
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
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffff800010cf6658)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffff800010cf6658-ffff800010cf6b04: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c0dfcf54)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
c0dfcf54-c0dfd43c: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (c000000000e1cba0)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
c000000000e1cba0-c000000000e1d284: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffe000841d9c)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffe000841d9c-ffffffe0008421f0: __inet6_bind (STB_LOCAL)
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
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff819d5200)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff819d5200-ffffffff819d5839: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81991fc0)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81991fc0-ffffffff819925f9: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a3fc80)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81a3fc80-ffffffff81a402b9: __inet6_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __inet6_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81a4b7c0)
Location: net/ipv6/af_inet6.c:274
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_bind
```
**Symbols:**

```
ffffffff81a4b7c0-ffffffff81a4bea8: __inet6_bind (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_bind_address_no_port</code>
</li>
<li>
<b>Param removed. </b>
<code>bool with_lock</code>
</li>
</ul>
</details>
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
