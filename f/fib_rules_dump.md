# Function: <code>fib_rules_dump</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8186eec0)
Location: net/core/fib_rules.c:331
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff8186eec0-ffffffff8186ef89: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818bffc0)
Location: net/core/fib_rules.c:356
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff818bffc0-ffffffff818c0089: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818e8f10)
Location: net/core/fib_rules.c:356
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff818e8f10-ffffffff818e8fd9: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81938930)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81938930-ffffffff819389f9: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8196b7f0)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff8196b7f0-ffffffff8196b8b9: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a40be0)
Location: net/core/fib_rules.c:355
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81a40be0-ffffffff81a40ce6: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a41e60)
Location: net/core/fib_rules.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81a41e60-ffffffff81a41f1e: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81a26b30)
Location: net/core/fib_rules.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81a26b30-ffffffff81a26bfc: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81adb8e0)
Location: net/core/fib_rules.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81adb8e0-ffffffff81adb9ac: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81c5de40)
Location: net/core/fib_rules.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81c5de40-ffffffff81c5df76: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e14640)
Location: net/core/fib_rules.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81e14640-ffffffff81e14776: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81e87f50)
Location: net/core/fib_rules.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81e87f50-ffffffff81e88086: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff81f49f60)
Location: net/core/fib_rules.c:377
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff81f49f60-ffffffff81f4a096: fib_rules_dump (STB_GLOBAL)
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
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffff800010c11e18)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffff800010c11e18-ffff800010c11eec: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (c0d29b38)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
c0d29b38-c0d29bfc: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (c000000000cfe940)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
c000000000cfe940-c000000000cfea64: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffe00078deca)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffe00078deca-ffffffe00078df5c: fib_rules_dump (STB_GLOBAL)
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
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8190b7c0)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff8190b7c0-ffffffff8190b889: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c5580)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff818c5580-ffffffff818c5649: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8195c7f0)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff8195c7f0-ffffffff8195c8b9: fib_rules_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_rules_dump(struct net *net, struct notifier_block *nb, int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8197ea30)
Location: net/core/fib_rules.c:353
Inline: False
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rules_dump
  - net/ipv4/ipmr.c:ipmr_rules_dump
  - net/ipv6/ip6mr.c:ip6mr_rules_dump
  - net/ipv6/fib6_rules.c:fib6_rules_dump
```
**Symbols:**

```
ffffffff8197ea30-ffffffff8197eaf9: fib_rules_dump (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
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
