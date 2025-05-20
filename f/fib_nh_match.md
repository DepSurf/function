# Function: <code>fib_nh_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179c5d0)
Location: net/ipv4/fib_semantics.c:620
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8179c5d0-ffffffff8179c7e4: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8180a150)
Location: net/ipv4/fib_semantics.c:623
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8180a150-ffffffff8180a364: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183b260)
Location: net/ipv4/fib_semantics.c:624
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8183b260-ffffffff8183b474: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185cb50)
Location: net/ipv4/fib_semantics.c:639
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8185cb50-ffffffff8185cd4e: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818dca40)
Location: net/ipv4/fib_semantics.c:632
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff818dca40-ffffffff818dcc52: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81933610)
Location: net/ipv4/fib_semantics.c:632
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81933610-ffffffff81933809: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81962b00)
Location: net/ipv4/fib_semantics.c:630
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81962b00-ffffffff81962cf9: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff819cb093-ffffffff819cb0b4: fib_nh_match.cold (STB_LOCAL)
ffffffff819c8740-ffffffff819c8b66: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819ff300)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff819ff300-ffffffff819ff72d: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aee880)
Location: net/ipv4/fib_semantics.c:841
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81aee880-ffffffff81aeec7e: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afb7e0)
Location: net/ipv4/fib_semantics.c:841
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81afb7e0-ffffffff81afbbde: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae6f20)
Location: net/ipv4/fib_semantics.c:842
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81ae6f20-ffffffff81ae7339: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:872
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81d3cce4-ffffffff81d3cd7c: fib_nh_match.cold (STB_LOCAL)
ffffffff81ba6c20-ffffffff81ba7127: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:874
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81f0952e-ffffffff81f095ab: fib_nh_match.cold (STB_LOCAL)
ffffffff81d395b0-ffffffff81d39a6b: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:876
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff820b0e0a-ffffffff820b0e86: fib_nh_match.cold (STB_LOCAL)
ffffffff81f01e90-ffffffff81f02362: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:876
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff82132094-ffffffff82132110: fib_nh_match.cold (STB_LOCAL)
ffffffff81f618f0-ffffffff81f61dc2: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fib_nh_match(struct net *net, struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:877
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff82213a52-ffffffff82213ace: fib_nh_match.cold (STB_LOCAL)
ffffffff82027ec0-ffffffff82028394: fib_nh_match (STB_GLOBAL)
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
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb7800)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffff800010cb7800-ffff800010cb7bf0: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc2930)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
c0dc2930-c0dc2d1c: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dcfe40)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
c000000000dcfe40-c000000000dd03b0: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080ea68)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffe00080ea68-ffffffe00080ecf6: fib_nh_match (STB_GLOBAL)
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
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199f0a0)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8199f0a0-ffffffff8199f4cd: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81958b60)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81958b60-ffffffff81958f8d: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a09940)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81a09940-ffffffff81a09d6d: fib_nh_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_nh_match(struct fib_config *cfg, struct fib_info *fi, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a140f0)
Location: net/ipv4/fib_semantics.c:832
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81a140f0-ffffffff81a1451d: fib_nh_match (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
<b>Param reordered. </b>
<code>cfg, fi, extack</code> ➡️ <code>net, cfg, fi, extack</code>
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
