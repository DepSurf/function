# Function: <code>fib_table_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib_table_delete(struct fib_table *tb, struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff817a0aa0)
Location: net/ipv4/fib_trie.c:1490
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff817a0aa0-ffffffff817a0de9: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib_table_delete(struct fib_table *tb, struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8180e710)
Location: net/ipv4/fib_trie.c:1489
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8180e710-ffffffff8180ea6b: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183fbf0)
Location: net/ipv4/fib_trie.c:1601
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8183fbf0-ffffffff8183ff59: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81861140)
Location: net/ipv4/fib_trie.c:1523
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81861140-ffffffff81861534: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e1220)
Location: net/ipv4/fib_trie.c:1521
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff818e1220-ffffffff818e1657: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81937dd0)
Location: net/ipv4/fib_trie.c:1545
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81937dd0-ffffffff81938183: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819677c0)
Location: net/ipv4/fib_trie.c:1545
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff819677c0-ffffffff81967b73: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cd9b0)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff819cd9b0-ffffffff819cdd69: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a04500)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81a04500-ffffffff81a048b9: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af4030)
Location: net/ipv4/fib_trie.c:1661
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81af4030-ffffffff81af42ff: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81b00e30)
Location: net/ipv4/fib_trie.c:1661
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81b00e30-ffffffff81b010ff: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aec4d0)
Location: net/ipv4/fib_trie.c:1698
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81aec4d0-ffffffff81aec7b6: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81bac810)
Location: net/ipv4/fib_trie.c:1702
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81bac810-ffffffff81bacaec: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3f6b0)
Location: net/ipv4/fib_trie.c:1709
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81d3f6b0-ffffffff81d3f9ac: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f082c0)
Location: net/ipv4/fib_trie.c:1711
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81f082c0-ffffffff81f085bc: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f67dd0)
Location: net/ipv4/fib_trie.c:1711
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81f67dd0-ffffffff81f680c4: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202e3b0)
Location: net/ipv4/fib_trie.c:1713
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8202e3b0-ffffffff8202e6a4: fib_table_delete (STB_GLOBAL)
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
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbd088)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffff800010cbd088-ffff800010cbd46c: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc89f0)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
c0dc89f0-c0dc8dfc: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd6fe0)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
c000000000dd6fe0-c000000000dd74f4: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe000813436)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffe000813436-ffffffe0008137a0: fib_table_delete (STB_GLOBAL)
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
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a42a0)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff819a42a0-ffffffff819a4659: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195dd60)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8195dd60-ffffffff8195e119: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0eb40)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81a0eb40-ffffffff81a0eef9: fib_table_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_table_delete(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a19390)
Location: net/ipv4/fib_trie.c:1547
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_delroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81a19390-ffffffff81a19749: fib_table_delete (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>tb, cfg</code> ➡️ <code>net, tb, cfg</code>
</li>
</ul>
</details>
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
