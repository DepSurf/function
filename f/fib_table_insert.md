# Function: <code>fib_table_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fib_table_insert(struct fib_table *tb, struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff817a0630)
Location: net/ipv4/fib_trie.c:1081
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff817a0630-ffffffff817a0a9d: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fib_table_insert(struct fib_table *tb, struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8180e210)
Location: net/ipv4/fib_trie.c:1079
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8180e210-ffffffff8180e710: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183f6c0)
Location: net/ipv4/fib_trie.c:1198
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8183f6c0-ffffffff8183fbe5: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81860ba0)
Location: net/ipv4/fib_trie.c:1119
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81860ba0-ffffffff8186113a: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e0c20)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff818e0c20-ffffffff818e1213: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81937890)
Location: net/ipv4/fib_trie.c:1124
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81937890-ffffffff81937dc6: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81967280)
Location: net/ipv4/fib_trie.c:1124
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81967280-ffffffff819677b6: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cd470)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff819cd470-ffffffff819cd9a3: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a03fc0)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81a03fc0-ffffffff81a044f3: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af31c0)
Location: net/ipv4/fib_trie.c:1168
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81af31c0-ffffffff81af38b4: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81b000d0)
Location: net/ipv4/fib_trie.c:1168
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81b000d0-ffffffff81b007c4: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aeb730)
Location: net/ipv4/fib_trie.c:1203
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81aeb730-ffffffff81aebe46: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81bab950)
Location: net/ipv4/fib_trie.c:1207
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81bab950-ffffffff81bac067: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3e7e0)
Location: net/ipv4/fib_trie.c:1215
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81d3e7e0-ffffffff81d3eebf: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f073d0)
Location: net/ipv4/fib_trie.c:1215
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81f073d0-ffffffff81f07a8d: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f66ea0)
Location: net/ipv4/fib_trie.c:1215
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81f66ea0-ffffffff81f67561: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202d480)
Location: net/ipv4/fib_trie.c:1216
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8202d480-ffffffff8202db41: fib_table_insert (STB_GLOBAL)
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
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbcb80)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffff800010cbcb80-ffff800010cbd088: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc8494)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
c0dc8494-c0dc89f0: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd69a0)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
c000000000dd69a0-c000000000dd6fe0: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe000812f68)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffe000812f68-ffffffe000813436: fib_table_insert (STB_GLOBAL)
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
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a3d60)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff819a3d60-ffffffff819a4293: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195d820)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff8195d820-ffffffff8195dd53: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0e600)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81a0e600-ffffffff81a0eb33: fib_table_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_table_insert(struct net *net, struct fib_table *tb, struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a18e50)
Location: net/ipv4/fib_trie.c:1120
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:inet_rtm_newroute
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81a18e50-ffffffff81a19383: fib_table_insert (STB_GLOBAL)
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
