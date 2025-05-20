# Function: <code>__inet_hash_connect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81762f10)
Location: net/ipv4/inet_hashtables.c:503
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81762f10-ffffffff817632b8: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cf380)
Location: net/ipv4/inet_hashtables.c:541
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff817cf380-ffffffff817cf774: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817ff170)
Location: net/ipv4/inet_hashtables.c:543
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff817ff170-ffffffff817ff564: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8181f3e0)
Location: net/ipv4/inet_hashtables.c:534
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff8181f3e0-ffffffff8181f79d: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8189e340)
Location: net/ipv4/inet_hashtables.c:538
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff8189e340-ffffffff8189e703: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f2db0)
Location: net/ipv4/inet_hashtables.c:659
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff818f2db0-ffffffff818f316d: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81920840)
Location: net/ipv4/inet_hashtables.c:624
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81920840-ffffffff81920c87: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: net/ipv4/inet_hashtables.c:620
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff8198367a-ffffffff8198369d: __inet_hash_connect.cold (STB_LOCAL)
ffffffff81983190-ffffffff819835c6: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b9a00)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff819b9a00-ffffffff819b9e3c: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa4460)
Location: net/ipv4/inet_hashtables.c:620
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81aa4460-ffffffff81aa48b7: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aaeab0)
Location: net/ipv4/inet_hashtables.c:712
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81aaeab0-ffffffff81aaef15: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a99cf0)
Location: net/ipv4/inet_hashtables.c:723
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81a99cf0-ffffffff81a9a22d: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b55160)
Location: net/ipv4/inet_hashtables.c:725
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81b55160-ffffffff81b5569e: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u64 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2d10)
Location: net/ipv4/inet_hashtables.c:691
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81ce2d10-ffffffff81ce3258: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u64 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea5120)
Location: net/ipv4/inet_hashtables.c:992
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81ea5120-ffffffff81ea583b: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u64 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f038b0)
Location: net/ipv4/inet_hashtables.c:982
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81f038b0-ffffffff81f03fc2: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u64 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc7b40)
Location: net/ipv4/inet_hashtables.c:994
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81fc7b40-ffffffff81fc8314: __inet_hash_connect (STB_GLOBAL)
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
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6b1b0)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffff800010c6b1b0-ffff800010c6b6a8: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d7a270)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
c0d7a270-c0d7a6ec: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d70690)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
c000000000d70690-c000000000d70c38: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d0e68)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffe0007d0e68-ffffffe0007d1252: __inet_hash_connect (STB_GLOBAL)
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
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81959870)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81959870-ffffffff81959cac: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81913360)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff81913360-ffffffff8191379c: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c4040)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff819c4040-ffffffff819c447c: __inet_hash_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __inet_hash_connect(struct inet_timewait_death_row *death_row, struct sock *sk, u32 port_offset, int (*check_established)(struct inet_timewait_death_row *, struct sock *, __u16, struct inet_timewait_sock **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cdab0)
Location: net/ipv4/inet_hashtables.c:619
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_hash_connect
  - net/ipv6/inet6_hashtables.c:inet6_hash_connect
```
**Symbols:**

```
ffffffff819cdab0-ffffffff819cdf00: __inet_hash_connect (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 port_offset</code> ➡️ <code>u64 port_offset</code>
</li>
</ul>
</details>
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
