# Function: <code>fib_info_notify_update</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819ce0f0)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff819ce0f0-ffffffff819ce253: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a04c50)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81a04c50-ffffffff81a04db2: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af4670)
Location: net/ipv4/fib_trie.c:2116
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81af4670-ffffffff81af46c8: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81b01470)
Location: net/ipv4/fib_trie.c:2107
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81b01470-ffffffff81b014c4: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aecb40)
Location: net/ipv4/fib_trie.c:2144
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81aecb40-ffffffff81aecc6c: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2148
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81d3da1b-ffffffff81d3da84: fib_info_notify_update.cold (STB_LOCAL)
ffffffff81bacef0-ffffffff81bad045: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2157
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81f0a302-ffffffff81f0a36b: fib_info_notify_update.cold (STB_LOCAL)
ffffffff81d3fe20-ffffffff81d3ffb1: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2159
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff820b1bcc-ffffffff820b1c35: fib_info_notify_update.cold (STB_LOCAL)
ffffffff81f08a60-ffffffff81f08bf1: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2159
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff82132e04-ffffffff82132e6d: fib_info_notify_update.cold (STB_LOCAL)
ffffffff81f68570-ffffffff81f68701: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:2165
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff822147e5-ffffffff8221484e: fib_info_notify_update.cold (STB_LOCAL)
ffffffff8202ebf0-ffffffff8202ed81: fib_info_notify_update (STB_GLOBAL)
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
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbd838)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffff800010cbd838-ffff800010cbd984: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc91d0)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
c0dc91d0-c0dc9334: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd7a60)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
c000000000dd7a60-c000000000dd7c48: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe000813af0)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffe000813af0-ffffffe000813c40: fib_info_notify_update (STB_GLOBAL)
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
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a49f0)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff819a49f0-ffffffff819a4b52: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195e4b0)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff8195e4b0-ffffffff8195e612: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0f290)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81a0f290-ffffffff81a0f3f2: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib_info_notify_update(struct net *net, struct nl_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a19ae0)
Location: net/ipv4/fib_trie.c:2005
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:__nexthop_replace_notify
```
**Symbols:**

```
ffffffff81a19ae0-ffffffff81a19c42: fib_info_notify_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
