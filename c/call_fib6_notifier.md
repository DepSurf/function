# Function: <code>call_fib6_notifier</code>

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
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81943110)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81943110-ffffffff81943127: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff8199bf20)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff8199bf20-ffffffff8199bf37: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff819d2870)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff819d2870-ffffffff819d2887: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a416d0)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81a416d0-ffffffff81a416e7: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a78330)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81a78330-ffffffff81a78347: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81b726a0)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81b726a0-ffffffff81b726b6: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81b81410)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81b81410-ffffffff81b81426: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81b70020)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81b70020-ffffffff81b70036: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81c38300)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81c38300-ffffffff81c38316: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81dd5f50)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81dd5f50-ffffffff81dd5f70: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81fa77a0)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81fa77a0-ffffffff81fa77c0: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff82008000)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff82008000-ffffffff82008020: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff820d6f20)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff820d6f20-ffffffff820d6f40: call_fib6_notifier (STB_GLOBAL)
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
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffff800010d41938)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffff800010d41938-ffff800010d4198c: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (c0e44310)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
c0e44310-c0e44334: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (c000000000e76580)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
c000000000e76580-c000000000e765bc: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffe00087cfdc)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffe00087cfdc-ffffffe00087d022: call_fib6_notifier (STB_GLOBAL)
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
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a179c0)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81a179c0-ffffffff81a179d7: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff819d4780)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff819d4780-ffffffff819d4797: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a82440)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81a82440-ffffffff81a82457: call_fib6_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib6_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a8ed50)
Location: net/ipv6/fib6_notifier.c:10
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_node_dump
```
**Symbols:**

```
ffffffff81a8ed50-ffffffff81a8ed67: call_fib6_notifier (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>nb, net, event_type, info</code> ➡️ <code>nb, event_type, info</code>
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
