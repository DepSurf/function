# Function: <code>rhashtable_free_and_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff813ffff0)
Location: lib/rhashtable.c:821
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
```
**Symbols:**

```
ffffffff813ffff0-ffffffff814000a5: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81447720)
Location: lib/rhashtable.c:826
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - lib/rhashtable.c:rhashtable_destroy
```
**Symbols:**

```
ffffffff81447720-ffffffff814477d5: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81466030)
Location: lib/rhashtable.c:974
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff81466030-ffffffff81466110: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b2b0)
Location: lib/rhashtable.c:1053
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff8146b2b0-ffffffff8146b3c4: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814975a0)
Location: lib/rhashtable.c:1056
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff814975a0-ffffffff814976b8: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc460)
Location: lib/rhashtable.c:1147
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff814cc460-ffffffff814cc583: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0bf0)
Location: lib/rhashtable.c:1138
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff814e0bf0-ffffffff814e0d13: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150c8a0)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff8150c8a0-ffffffff8150c9e8: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152a6f0)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff8152a6f0-ffffffff8152a838: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e800)
Location: lib/rhashtable.c:1130
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff8158e840-ffffffff8158e982: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815ab370)
Location: lib/rhashtable.c:1130
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff815ab3b0-ffffffff815ab4e8: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b6950)
Location: lib/rhashtable.c:1130
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff815b6810-ffffffff815b694f: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8161cec0)
Location: lib/rhashtable.c:1130
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff81cdacc5-ffffffff81cdace0: rhashtable_free_and_destroy.cold (STB_LOCAL)
ffffffff8161cd80-ffffffff8161ceb7: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff816ea770)
Location: lib/rhashtable.c:1130
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff81e93586-ffffffff81e935a1: rhashtable_free_and_destroy.cold (STB_LOCAL)
ffffffff816ea600-ffffffff816ea76a: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff817da9d0)
Location: lib/rhashtable.c:1134
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff82078708-ffffffff82078723: rhashtable_free_and_destroy.cold (STB_LOCAL)
ffffffff817da850-ffffffff817da9ba: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff81819c40)
Location: lib/rhashtable.c:1134
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff820f8c5c-ffffffff820f8c77: rhashtable_free_and_destroy.cold (STB_LOCAL)
ffffffff81819aa0-ffffffff81819c2c: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8185ef90)
Location: lib/rhashtable.c:1134
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_destroy
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ioam6.c:ioam6_net_exit
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff821d677d-ffffffff821d6798: rhashtable_free_and_destroy.cold (STB_LOCAL)
ffffffff8185edf0-ffffffff8185ef7c: rhashtable_free_and_destroy (STB_GLOBAL)
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
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010636110)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffff800010636110-ffff80001063626c: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dc048)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
c07dc048-c07dc1ac: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007db6b0)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
c0000000007db6b0-c0000000007db8c4: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe000463342)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffe000463342-ffffffe00046346a: rhashtable_free_and_destroy (STB_GLOBAL)
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
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81522cd0)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff81522cd0-ffffffff81522e18: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81512fb0)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff81512fb0-ffffffff815130f8: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151ed60)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff8151ed60-ffffffff8151eea8: rhashtable_free_and_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rhashtable_free_and_destroy(struct rhashtable *ht, void (*free_fn)(void *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81538780)
Location: lib/rhashtable.c:1123
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_destroy
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/ipmr.c:ipmr_free_table
  - net/ipv6/ip6mr.c:ip6mr_free_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
```
**Symbols:**

```
ffffffff81538780-ffffffff815388c5: rhashtable_free_and_destroy (STB_GLOBAL)
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
