# Function: <code>ip_rt_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179b200)
Location: net/ipv4/fib_frontend.c:576
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8179b200-ffffffff8179b6c5: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81808e00)
Location: net/ipv4/fib_frontend.c:576
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81808e00-ffffffff818092bc: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81839ef0)
Location: net/ipv4/fib_frontend.c:568
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81839ef0-ffffffff8183a3c3: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185b470)
Location: net/ipv4/fib_frontend.c:568
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8185b470-ffffffff8185b94a: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818db360)
Location: net/ipv4/fib_frontend.c:590
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff818db360-ffffffff818db83a: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81931ec0)
Location: net/ipv4/fib_frontend.c:595
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81931ec0-ffffffff81932398: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81961720)
Location: net/ipv4/fib_frontend.c:605
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81961720-ffffffff81961bf8: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c5ec0)
Location: net/ipv4/fib_frontend.c:618
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819c5ec0-ffffffff819c6364: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fca70)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819fca70-ffffffff819fcf14: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aeb7e0)
Location: net/ipv4/fib_frontend.c:611
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81aeb7e0-ffffffff81aeb93f: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af86f0)
Location: net/ipv4/fib_frontend.c:611
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81af86f0-ffffffff81af884f: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae3e10)
Location: net/ipv4/fib_frontend.c:613
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ae3e10-ffffffff81ae3f6f: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba3760)
Location: net/ipv4/fib_frontend.c:613
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ba3760-ffffffff81ba38bf: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d35fe0)
Location: net/ipv4/fib_frontend.c:616
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81d35fe0-ffffffff81d36140: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efe5f0)
Location: net/ipv4/fib_frontend.c:616
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81efe5f0-ffffffff81efe750: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5e080)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81f5e080-ffffffff81f5e1e0: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff82024640)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_routing_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff82024640-ffffffff820247a0: ip_rt_ioctl (STB_GLOBAL)
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
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb4ec8)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffff800010cb4ec8-ffff800010cb5030: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc0864)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
c0dc0864-c0dc09d0: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcc240)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
c000000000dcc240-c000000000dcc9d0: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080c9dc)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffe00080c9dc-ffffffe00080caee: ip_rt_ioctl (STB_GLOBAL)
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
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199c810)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8199c810-ffffffff8199ccb4: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819562d0)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819562d0-ffffffff81956774: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a070b0)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81a070b0-ffffffff81a07554: ip_rt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_rt_ioctl(struct net *net, unsigned int cmd, struct rtentry *rt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a11780)
Location: net/ipv4/fib_frontend.c:619
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81a11780-ffffffff81a11c9d: ip_rt_ioctl (STB_GLOBAL)
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
<code>struct rtentry *rt</code>
</li>
<li>
<b>Param removed. </b>
<code>void *arg</code>
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
