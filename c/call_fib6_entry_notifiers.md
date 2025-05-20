# Function: <code>call_fib6_entry_notifiers</code>

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
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct rt6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81921730)
Location: net/ipv6/ip6_fib.c:354
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81921730-ffffffff8192178e: call_fib6_entry_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197c2b0)
Location: net/ipv6/ip6_fib.c:402
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b1f90)
Location: net/ipv6/ip6_fib.c:401
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1f260)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a1f260-ffffffff81a1f2c2: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a55ee0)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a55ee0-ffffffff81a55f42: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4df2f)
Location: net/ipv6/ip6_fib.c:388
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
```
**Symbols:**

```
ffffffff81b4e740-ffffffff81b4e79a: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5cbc0)
Location: net/ipv6/ip6_fib.c:389
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b5d3c0-ffffffff81b5d41a: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4add6)
Location: net/ipv6/ip6_fib.c:389
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b4b5d0-ffffffff81b4b632: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c12116)
Location: net/ipv6/ip6_fib.c:390
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81c12910-ffffffff81c12972: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dad691)
Location: net/ipv6/ip6_fib.c:391
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81dade30-ffffffff81dade9e: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7d101)
Location: net/ipv6/ip6_fib.c:390
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81f7d910-ffffffff81f7d97e: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdd30e)
Location: net/ipv6/ip6_fib.c:390
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81fddb20-ffffffff81fddb8e: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820ab44e)
Location: net/ipv6/ip6_fib.c:390
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff820aabd0-ffffffff820aac3e: call_fib6_entry_notifiers (STB_GLOBAL)
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
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1a9c0)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffff800010d1a9c0-ffff800010d1aa50: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1fe00)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c0e1fe00-c0e1fe84: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e48d30)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c000000000e48d30-c000000000e48dbc: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085ed54)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffe00085ed54-ffffffe00085edb2: call_fib6_entry_notifiers (STB_GLOBAL)
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
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f5570)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819f5570-ffffffff819f55d2: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b2330)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819b2330-ffffffff819b2392: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5fff0)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a5fff0-ffffffff81a60052: call_fib6_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6c4b0)
Location: net/ipv6/ip6_fib.c:371
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a6c4b0-ffffffff81a6c512: call_fib6_entry_notifiers (STB_GLOBAL)
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
