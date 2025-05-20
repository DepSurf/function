# Function: <code>mr_dump</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81944760)
Location: net/ipv4/ipmr_base.c:330
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81944760-ffffffff819448f9: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81974a00)
Location: net/ipv4/ipmr_base.c:388
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81974a00-ffffffff81974b99: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819de530)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff819de530-ffffffff819de6c9: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a155d0)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81a155d0-ffffffff81a15769: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b06080)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81b06080-ffffffff81b061ea: mr_dump.part.0 (STB_LOCAL)
ffffffff81b061f0-ffffffff81b0624c: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b14270)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81b14270-ffffffff81b143da: mr_dump.part.0 (STB_LOCAL)
ffffffff81b143e0-ffffffff81b1443c: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b020a0)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81b020a0-ffffffff81b0223d: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81bc3f40)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81bc3f40-ffffffff81bc40dd: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81d593a0)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81d593a0-ffffffff81d5956e: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81f232f0)
Location: net/ipv4/ipmr_base.c:396
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81f232f0-ffffffff81f234aa: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81f82e30)
Location: net/ipv4/ipmr_base.c:396
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81f82e30-ffffffff81f82ffd: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff820494b0)
Location: net/ipv4/ipmr_base.c:396
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff820494b0-ffffffff8204967d: mr_dump (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffff800010cd0c20)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffff800010cd0c20-ffff800010cd0e00: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c0ddb140)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
c0ddb140-c0ddb2e8: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c000000000def130)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
c000000000def130-c000000000def390: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffe000822842)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffe000822842-ffffffe00082298a: mr_dump (STB_GLOBAL)
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
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819b4c60)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff819b4c60-ffffffff819b4df9: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81971290)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81971290-ffffffff81971429: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a1f500)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81a1f500-ffffffff81a1f699: mr_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mr_dump(struct net *net, struct notifier_block *nb, short unsigned int family, int (*rules_dump)(struct net *, struct notifier_block *), struct mr_table * (*mr_iter)(struct net *, struct mr_table *), rwlock_t *mrt_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a2aa00)
Location: net/ipv4/ipmr_base.c:387
Inline: True
Direct callers:
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/ip6mr.c:ip6mr_dump
```
**Symbols:**

```
ffffffff81a2aa00-ffffffff81a2ab9a: mr_dump (STB_GLOBAL)
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
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*rules_dump)(struct net *, struct notifier_block *)</code> ➡️ <code>int (*rules_dump)(struct net *, struct notifier_block *, struct netlink_ext_ack *)</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>rwlock_t *mrt_lock</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, nb, family, rules_dump, mr_iter, mrt_lock, extack</code> ➡️ <code>net, nb, family, rules_dump, mr_iter, extack</code>
</li>
</ul>
</details>
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
