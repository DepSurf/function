# Function: <code>call_fib_notifier</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183e9f0)
Location: net/ipv4/fib_trie.c:102
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:register_fib_notifier
  - net/ipv4/fib_trie.c:register_fib_notifier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81862260)
Location: net/ipv4/fib_notifier.c:11
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_notify
  - net/ipv4/fib_rules.c:fib_rules_notify
```
**Symbols:**

```
ffffffff81862260-ffffffff81862277: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff8186a450)
Location: net/core/fib_notifier.c:12
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv4/ipmr.c:ipmr_dump
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff8186a450-ffffffff8186a46d: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818ba180)
Location: net/core/fib_notifier.c:12
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff818ba180-ffffffff818ba1b6: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818e1000)
Location: net/core/fib_notifier.c:12
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff818e1000-ffffffff818e1036: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff8192f7f0)
Location: net/core/fib_notifier.c:12
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff8192f7f0-ffffffff8192f826: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81961a60)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81961a60-ffffffff81961a96: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a35060)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81a35060-ffffffff81a3508c: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a373a0)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81a373a0-ffffffff81a373cc: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a1e500)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81a1e500-ffffffff81a1e52b: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81ad25a0)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81ad25a0-ffffffff81ad25cb: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81c4ffa0)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81c4ffa0-ffffffff81c4ffd7: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81e052f0)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81e052f0-ffffffff81e05327: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81e77b40)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81e77b40-ffffffff81e77b77: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81f37b00)
Location: net/core/fib_notifier.c:18
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81f37b00-ffffffff81f37b37: call_fib_notifier (STB_GLOBAL)
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
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffff800010c056e0)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffff800010c056e0-ffff800010c05744: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (c0d1e808)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
c0d1e808-c0d1e848: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (c000000000cef840)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
c000000000cef840-c000000000cef8c4: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffe000783ede)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffe000783ede-ffffffe000783f46: call_fib_notifier (STB_GLOBAL)
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
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81901a30)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81901a30-ffffffff81901a66: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818bb860)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff818bb860-ffffffff818bb896: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81952a60)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff81952a60-ffffffff81952a96: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib_notifier(struct notifier_block *nb, struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff819744d0)
Location: net/core/fib_notifier.c:19
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_dump
  - net/ipv4/fib_notifier.c:call_fib4_notifier
  - net/ipv6/fib6_notifier.c:call_fib6_notifier
```
**Symbols:**

```
ffffffff819744d0-ffffffff81974506: call_fib_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
