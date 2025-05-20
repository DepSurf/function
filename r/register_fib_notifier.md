# Function: <code>register_fib_notifier</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183e990)
Location: net/ipv4/fib_trie.c:155
Inline: False
```
**Symbols:**

```
ffffffff8183e990-ffffffff8183eb74: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81862170)
Location: net/ipv4/fib_notifier.c:54
Inline: False
```
**Symbols:**

```
ffffffff81862170-ffffffff81862237: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff8186a560)
Location: net/core/fib_notifier.c:83
Inline: False
```
**Symbols:**

```
ffffffff8186a560-ffffffff8186a663: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818ba2f0)
Location: net/core/fib_notifier.c:91
Inline: False
```
**Symbols:**

```
ffffffff818ba2f0-ffffffff818ba3f3: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818e1170)
Location: net/core/fib_notifier.c:91
Inline: False
```
**Symbols:**

```
ffffffff818e1170-ffffffff818e1273: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff8192f960)
Location: net/core/fib_notifier.c:91
Inline: False
```
**Symbols:**

```
ffffffff8192f960-ffffffff8192fa62: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81961bd0)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
ffffffff81961bd0-ffffffff81961cd8: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a351a0)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81a351a0-ffffffff81a352b4: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a37500)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81a37500-ffffffff81a3762e: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a1e660)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81a1e660-ffffffff81a1e78b: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81ad2700)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81ad2700-ffffffff81ad282b: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81c50140)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81c50140-ffffffff81c50278: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81e054d0)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81e054d0-ffffffff81e05608: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81e77d20)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81e77d20-ffffffff81e77e58: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_fib_notifier(struct net *net, struct notifier_block *nb, void (*cb)(struct notifier_block *), struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81f37ce0)
Location: net/core/fib_notifier.c:99
Inline: False
```
**Symbols:**

```
ffffffff81f37ce0-ffffffff81f37e18: register_fib_notifier (STB_GLOBAL)
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
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffff800010c058e8)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
ffff800010c058e8-ffff800010c05a60: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (c0d1e990)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
c0d1e990-c0d1ead4: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (c000000000cefb20)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
c000000000cefb20-c000000000cefcf8: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffe0007840d2)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
ffffffe0007840d2-ffffffe0007841f8: register_fib_notifier (STB_GLOBAL)
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
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81901ba0)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
ffffffff81901ba0-ffffffff81901ca8: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818bb9d0)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
ffffffff818bb9d0-ffffffff818bbad8: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81952bd0)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
ffffffff81952bd0-ffffffff81952cd8: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_fib_notifier(struct notifier_block *nb, void (*cb)(struct notifier_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81974670)
Location: net/core/fib_notifier.c:101
Inline: False
```
**Symbols:**

```
ffffffff81974670-ffffffff81974793: register_fib_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param reordered. </b>
<code>nb, cb</code> ➡️ <code>net, nb, cb, extack</code>
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
