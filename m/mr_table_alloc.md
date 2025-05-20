# Function: <code>mr_table_alloc</code>

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
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81944900)
Location: net/ipv4/ipmr_base.c:31
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff81944900-ffffffff819449e1: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81974ba0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff81974ba0-ffffffff81974c81: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819de6d0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff819de6d0-ffffffff819de7c1: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a15770)
Location: net/ipv4/ipmr_base.c:32
Inline: False
```
**Symbols:**

```
ffffffff81a15770-ffffffff81a15861: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b06490)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b06490-ffffffff81b06581: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b14680)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b14680-ffffffff81b14771: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b02480)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b02480-ffffffff81b02571: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81bc43f0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81bc43f0-ffffffff81bc44e1: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81d592a0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81d592a0-ffffffff81d59397: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81f238a0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f238a0-ffffffff81f23997: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81f833f0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f833f0-ffffffff81f834e7: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff82049a70)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff82049a70-ffffffff82049b96: mr_table_alloc (STB_GLOBAL)
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
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffff800010cd08d0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
```
**Symbols:**

```
ffff800010cd08d0-ffff800010cd09c4: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c0ddac40)
Location: net/ipv4/ipmr_base.c:32
Inline: False
```
**Symbols:**

```
c0ddac40-c0ddad24: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c000000000def390)
Location: net/ipv4/ipmr_base.c:32
Inline: False
```
**Symbols:**

```
c000000000def390-c000000000def520: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffe00082298a)
Location: net/ipv4/ipmr_base.c:32
Inline: False
```
**Symbols:**

```
ffffffe00082298a-ffffffe000822a5a: mr_table_alloc (STB_GLOBAL)
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
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819b4e00)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff819b4e00-ffffffff819b4ef1: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81971430)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff81971430-ffffffff81971521: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a1f6a0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff81a1f6a0-ffffffff81a1f791: mr_table_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mr_table *mr_table_alloc(struct net *net, u32 id, struct mr_table_ops *ops, void (*expire_func)(struct timer_list *), void (*table_set)(struct mr_table *, struct net *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a2aba0)
Location: net/ipv4/ipmr_base.c:32
Inline: False
```
**Symbols:**

```
ffffffff81a2aba0-ffffffff81a2ac91: mr_table_alloc (STB_GLOBAL)
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
