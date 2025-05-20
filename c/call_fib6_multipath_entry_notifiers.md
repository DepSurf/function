# Function: <code>call_fib6_multipath_entry_notifiers</code>

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
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1f2d0)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a1f2d0-ffffffff81a1f335: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a55f50)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a55f50-ffffffff81a55fb5: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4e7a0)
Location: net/ipv6/ip6_fib.c:402
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b4e7a0-ffffffff81b4e7fd: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5d420)
Location: net/ipv6/ip6_fib.c:403
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b5d420-ffffffff81b5d47d: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4b640)
Location: net/ipv6/ip6_fib.c:403
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b4b640-ffffffff81b4b6a6: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c12980)
Location: net/ipv6/ip6_fib.c:404
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81c12980-ffffffff81c129e6: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dadea0)
Location: net/ipv6/ip6_fib.c:405
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81dadea0-ffffffff81dadf15: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7d990)
Location: net/ipv6/ip6_fib.c:404
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81f7d990-ffffffff81f7da05: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fddba0)
Location: net/ipv6/ip6_fib.c:404
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81fddba0-ffffffff81fddc15: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820aac50)
Location: net/ipv6/ip6_fib.c:404
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff820aac50-ffffffff820aacc5: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
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
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1aa50)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffff800010d1aa50-ffff800010d1aae8: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1fe84)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c0e1fe84-c0e1ff08: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e48dc0)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c000000000e48dc0-c000000000e48e50: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085edb2)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffe00085edb2-ffffffe00085ee1a: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
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
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f55e0)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819f55e0-ffffffff819f5645: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b23a0)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819b23a0-ffffffff819b2405: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a60060)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a60060-ffffffff81a600c5: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net *net, enum fib_event_type event_type, struct fib6_info *rt, unsigned int nsiblings, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6c520)
Location: net/ipv6/ip6_fib.c:385
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a6c520-ffffffff81a6c585: call_fib6_multipath_entry_notifiers (STB_GLOBAL)
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
