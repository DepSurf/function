# Function: <code>call_netevent_notifiers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81724210)
Location: net/core/netevent.c:63
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_update
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81724210-ffffffff8172422d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff8178dcc0)
Location: net/core/netevent.c:63
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff8178dcc0-ffffffff8178dcdd: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff817bb590)
Location: net/core/netevent.c:63
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff817bb590-ffffffff817bb5ad: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff817d9d10)
Location: net/core/netevent.c:63
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff817d9d10-ffffffff817d9d2d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81854480)
Location: net/core/netevent.c:63
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81854480-ffffffff8185449d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff8189fbc0)
Location: net/core/netevent.c:63
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff8189fbc0-ffffffff8189fbdd: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff818c2590)
Location: net/core/netevent.c:63
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff818c2590-ffffffff818c25ad: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff8190ed40)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff8190ed40-ffffffff8190ed5d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff819413b0)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff819413b0-ffffffff819413cd: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81a11020)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81a11020-ffffffff81a1103d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81a11390)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81a11390-ffffffff81a113ad: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff819f81f0)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff819f81f0-ffffffff819f820d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81aa9e60)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81aa9e60-ffffffff81aa9e7d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81c22330)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81c22330-ffffffff81c22357: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81dd4720)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81dd4720-ffffffff81dd4747: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81e454c0)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81e454c0-ffffffff81e454e7: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81f04150)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81f04150-ffffffff81f04177: call_netevent_notifiers (STB_GLOBAL)
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
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffff800010be1120)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffff800010be1120-ffff800010be115c: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (c0cfb2f0)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
c0cfb2f0-c0cfb31c: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (c000000000cc20d0)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
c000000000cc20d0-c000000000cc2118: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffe00076740a)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffe00076740a-ffffffe000767444: call_netevent_notifiers (STB_GLOBAL)
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
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff818e1380)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff818e1380-ffffffff818e139d: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff8189b1c0)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff8189b1c0-ffffffff8189b1dd: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff819323b0)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff819323b0-ffffffff819323cd: call_netevent_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_netevent_notifiers(long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netevent.c (ffffffff81953a80)
Location: net/core/netevent.c:59
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_proc_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81953a80-ffffffff81953a9d: call_netevent_notifiers (STB_GLOBAL)
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
