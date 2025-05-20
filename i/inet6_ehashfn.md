# Function: <code>inet6_ehashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81801c40)
Location: net/ipv6/inet6_hashtables.c:26
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
**Symbols:**

```
ffffffff81801c40-ffffffff81801ded: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81872fb0)
Location: net/ipv6/inet6_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81872fb0-ffffffff81873159: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff818a75d0)
Location: net/ipv6/inet6_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff818a75d0-ffffffff818a7779: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff818cded0)
Location: net/ipv6/inet6_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff818cded0-ffffffff818ce079: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81952cf0)
Location: net/ipv6/inet6_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81952cf0-ffffffff81952e9d: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819ac280)
Location: net/ipv6/inet6_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff819ac280-ffffffff819ac429: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e2e60)
Location: net/ipv6/inet6_hashtables.c:28
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff819e2e60-ffffffff819e3009: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a51bf0)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81a51bf0-ffffffff81a51d9a: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a887f0)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81a887f0-ffffffff81a8899d: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b83e30)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81b83e30-ffffffff81b83fdd: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b93690)
Location: net/ipv6/inet6_hashtables.c:26
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81b93690-ffffffff81b9383d: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81b827a0)
Location: net/ipv6/inet6_hashtables.c:26
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81b827a0-ffffffff81b82952: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e870)
Location: net/ipv6/inet6_hashtables.c:26
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81c4e870-ffffffff81c4ea22: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81def1a0)
Location: net/ipv6/inet6_hashtables.c:26
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81def1a0-ffffffff81def371: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3250)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81fc3250-ffffffff81fc3421: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff82024060)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff82024060-ffffffff82024276: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff820f31d0)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff820f31d0-ffffffff820f33e6: inet6_ehashfn (STB_GLOBAL)
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
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffff800010d553e8)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffff800010d553e8-ffff800010d55600: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c0e5599c)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
c0e5599c-c0e55b6c: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (c000000000e8e200)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
c000000000e8e200-c000000000e8e458: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffe00088cbb0)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffe00088cbb0-ffffffe00088cdb4: inet6_ehashfn (STB_GLOBAL)
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
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a27e80)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81a27e80-ffffffff81a2802d: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff819e4c40)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff819e4c40-ffffffff819e4ded: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a93a30)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81a93a30-ffffffff81a93bdd: inet6_ehashfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 inet6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fb80)
Location: net/ipv6/inet6_hashtables.c:24
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
**Symbols:**

```
ffffffff81a9fb80-ffffffff81a9fd2d: inet6_ehashfn (STB_GLOBAL)
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
