# Function: <code>ip6_ins_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_ins_rt(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d6c20)
Location: net/ipv6/route.c:924
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff817d6c20-ffffffff817d6c8e: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_ins_rt(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818452b0)
Location: net/ipv6/route.c:929
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff818452b0-ffffffff8184531e: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_ins_rt(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81877020)
Location: net/ipv6/route.c:932
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81877020-ffffffff8187708e: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_ins_rt(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189c290)
Location: net/ipv6/route.c:952
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff8189c290-ffffffff8189c330: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_ins_rt(struct rt6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191ef50)
Location: net/ipv6/route.c:1015
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff8191ef50-ffffffff8191eff0: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81975720)
Location: net/ipv6/route.c:1162
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81975720-ffffffff81975777: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab370)
Location: net/ipv6/route.c:1165
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff819ab370-ffffffff819ab3c7: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18d00)
Location: net/ipv6/route.c:1315
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a18d00-ffffffff81a18d57: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4f960)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a4f960-ffffffff81a4f9b7: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b470a0)
Location: net/ipv6/route.c:1322
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81b470a0-ffffffff81b47126: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b55ca0)
Location: net/ipv6/route.c:1305
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81b55ca0-ffffffff81b55d26: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b438c0)
Location: net/ipv6/route.c:1308
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81b438c0-ffffffff81b43946: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0a440)
Location: net/ipv6/route.c:1308
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81c0a440-ffffffff81c0a4c6: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da5140)
Location: net/ipv6/route.c:1308
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81da5140-ffffffff81da51d0: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f74640)
Location: net/ipv6/route.c:1308
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81f74640-ffffffff81f746d0: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd46e0)
Location: net/ipv6/route.c:1307
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81fd46e0-ffffffff81fd4770: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a1ff0)
Location: net/ipv6/route.c:1309
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff820a1ff0-ffffffff820a2080: ip6_ins_rt (STB_GLOBAL)
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
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13868)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffff800010d13868-ffff800010d138d4: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19400)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
c0e19400-c0e19478: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e40190)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
c000000000e40190-c000000000e4020c: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008593a2)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffe0008593a2-ffffffe0008593e4: ip6_ins_rt (STB_GLOBAL)
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
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eeff0)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff819eeff0-ffffffff819ef047: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abdb0)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff819abdb0-ffffffff819abe07: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59a70)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a59a70-ffffffff81a59ac7: ip6_ins_rt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_ins_rt(struct net *net, struct fib6_info *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65cb0)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a65cb0-ffffffff81a65d07: ip6_ins_rt (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>rt</code> ➡️ <code>net, rt</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *rt</code> ➡️ <code>struct fib6_info *rt</code>
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
