# Function: <code>fib_notify</code>

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
In net/ipv4/fib_trie.c (ffffffff8183ea0a)
Location: net/ipv4/fib_trie.c:2037
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:register_fib_notifier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81861900)
Location: net/ipv4/fib_trie.c:1955
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:register_fib_notifier
```
**Symbols:**

```
ffffffff81861900-ffffffff81861a2f: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e1a00)
Location: net/ipv4/fib_trie.c:1951
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff818e1a00-ffffffff818e1b3b: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81938500)
Location: net/ipv4/fib_trie.c:1975
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81938500-ffffffff81938636: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81967ef0)
Location: net/ipv4/fib_trie.c:1984
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81967ef0-ffffffff81968026: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819ce260)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff819ce260-ffffffff819ce39c: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a04dc0)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81a04dc0-ffffffff81a04eff: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af46d0)
Location: net/ipv4/fib_trie.c:2184
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81af46d0-ffffffff81af4814: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81b014d0)
Location: net/ipv4/fib_trie.c:2175
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81b014d0-ffffffff81b01616: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aecc70)
Location: net/ipv4/fib_trie.c:2212
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81aecc70-ffffffff81aecdcd: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81bad050)
Location: net/ipv4/fib_trie.c:2216
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81bad050-ffffffff81bad1ad: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3ffc0)
Location: net/ipv4/fib_trie.c:2225
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81d3ffc0-ffffffff81d40141: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f08c10)
Location: net/ipv4/fib_trie.c:2227
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81f08c10-ffffffff81f08d91: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f68720)
Location: net/ipv4/fib_trie.c:2227
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81f68720-ffffffff81f688a1: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_notify(struct net *net, struct notifier_block *nb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202eda0)
Location: net/ipv4/fib_trie.c:2233
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff8202eda0-ffffffff8202ef21: fib_notify (STB_GLOBAL)
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
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbd988)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffff800010cbd988-ffff800010cbdac8: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc9334)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
c0dc9334-c0dc9478: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd7c50)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
c000000000dd7c50-c000000000dd7dec: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe000813c40)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffe000813c40-ffffffe000813d32: fib_notify (STB_GLOBAL)
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
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a4b60)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff819a4b60-ffffffff819a4c9f: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195e620)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff8195e620-ffffffff8195e75f: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0f400)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81a0f400-ffffffff81a0f53f: fib_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib_notify(struct net *net, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a19c50)
Location: net/ipv4/fib_trie.c:2057
Inline: False
Direct callers:
  - net/ipv4/fib_notifier.c:fib4_dump
```
**Symbols:**

```
ffffffff81a19c50-ffffffff81a19d8f: fib_notify (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
