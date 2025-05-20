# Function: <code>fib6_clean_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817dbfa0)
Location: net/ipv6/ip6_fib.c:1695
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_remove_prefsrc
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_mtu_change
```
**Symbols:**

```
ffffffff817dbfa0-ffffffff817dbfb5: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81849fcc)
Location: net/ipv6/ip6_fib.c:1697
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81849f60-ffffffff81849f75: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187be5c)
Location: net/ipv6/ip6_fib.c:1703
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff8187bdf0-ffffffff8187be05: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818a17fc)
Location: net/ipv6/ip6_fib.c:1745
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff818a1790-ffffffff818a17a5: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8192416c)
Location: net/ipv6/ip6_fib.c:1988
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81924100-ffffffff81924115: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8197c567)
Location: net/ipv6/ip6_fib.c:2043
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff8197c4e0-ffffffff8197c4f5: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b227e)
Location: net/ipv6/ip6_fib.c:2079
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff819b21d0-ffffffff819b21e8: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a2071a)
Location: net/ipv6/ip6_fib.c:2154
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81a20670-ffffffff81a20688: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5737a)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81a572d0-ffffffff81a572e8: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4f4da)
Location: net/ipv6/ip6_fib.c:2258
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81b4f430-ffffffff81b4f448: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5e15a)
Location: net/ipv6/ip6_fib.c:2262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81b5e0b0-ffffffff81b5e0c8: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4c3da)
Location: net/ipv6/ip6_fib.c:2263
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81b4c330-ffffffff81b4c348: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c136ea)
Location: net/ipv6/ip6_fib.c:2264
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81c13640-ffffffff81c13658: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81daed36)
Location: net/ipv6/ip6_fib.c:2265
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81daec60-ffffffff81daec87: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7e8a6)
Location: net/ipv6/ip6_fib.c:2264
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81f7e7b0-ffffffff81f7e7d7: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdeaad)
Location: net/ipv6/ip6_fib.c:2264
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81fde9c0-ffffffff81fde9e7: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820ac62d)
Location: net/ipv6/ip6_fib.c:2260
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff820ac540-ffffffff820ac567: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d1bfec)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffff800010d1beb0-ffff800010d1befc: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e21434)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
c0e21354-c0e21384: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e4a97c)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
c000000000e4a8b0-c000000000e4a8d0: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085fe6a)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffe00085fdaa-ffffffe00085fde8: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f6a0a)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff819f6960-ffffffff819f6978: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b37ca)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff819b3720-ffffffff819b3738: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6148a)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81a613e0-ffffffff81a613f8: fib6_clean_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6d94a)
Location: net/ipv6/ip6_fib.c:2155
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
Direct callers:
  - net/ipv6/route.c:rt6_mtu_change
  - net/ipv6/route.c:rt6_sync_down_dev
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:rt6_clean_tohost
  - net/ipv6/route.c:rt6_remove_prefsrc
```
**Symbols:**

```
ffffffff81a6d8a0-ffffffff81a6d8b8: fib6_clean_all (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*func)(struct rt6_info *, void *)</code> ➡️ <code>int (*func)(struct fib6_info *, void *)</code>
</li>
</ul>
</details>
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
