# Function: <code>call_fib6_notifiers</code>

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
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81943130)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffff81943130-ffffffff81943147: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff8199bf40)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8199bf40-ffffffff8199bf57: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff819d2890)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819d2890-ffffffff819d28a7: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a416f0)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffff81a416f0-ffffffff81a41707: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a78350)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffff81a78350-ffffffff81a78367: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81b726c0)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff81b726c0-ffffffff81b726d6: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81b81430)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff81b81430-ffffffff81b81446: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81b70040)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff81b70040-ffffffff81b70056: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81c38320)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff81c38320-ffffffff81c38336: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81dd5f70)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff81dd5f70-ffffffff81dd5f90: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81fa77d0)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff81fa77d0-ffffffff81fa77f0: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff82008030)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff82008030-ffffffff82008050: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff820d6f50)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
```
**Symbols:**

```
ffffffff820d6f50-ffffffff820d6f70: call_fib6_notifiers (STB_GLOBAL)
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
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffff800010d41990)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffff800010d41990-ffff800010d419dc: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (c0e44334)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
c0e44334-c0e44358: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (c000000000e765c0)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
c000000000e765c0-c000000000e765fc: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffe00087d022)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffe00087d022-ffffffe00087d060: call_fib6_notifiers (STB_GLOBAL)
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
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a179e0)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffff81a179e0-ffffffff81a179f7: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff819d47a0)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffff819d47a0-ffffffff819d47b7: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a82460)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffff81a82460-ffffffff81a82477: call_fib6_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib6_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_notifier.c (ffffffff81a8ed70)
Location: net/ipv6/fib6_notifier.c:18
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:call_fib6_multipath_entry_notifiers
  - net/ipv6/ip6_fib.c:call_fib6_entry_notifiers
```
**Symbols:**

```
ffffffff81a8ed70-ffffffff81a8ed87: call_fib6_notifiers (STB_GLOBAL)
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
