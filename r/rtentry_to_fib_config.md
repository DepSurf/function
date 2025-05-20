# Function: <code>rtentry_to_fib_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179b288)
Location: net/ipv4/fib_frontend.c:441
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81808e8a)
Location: net/ipv4/fib_frontend.c:440
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81839f7d)
Location: net/ipv4/fib_frontend.c:432
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185b4eb)
Location: net/ipv4/fib_frontend.c:432
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818db3db)
Location: net/ipv4/fib_frontend.c:454
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In net/ipv4/fib_frontend.c (ffffffff81931f21)
Location: net/ipv4/fib_frontend.c:459
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In net/ipv4/fib_frontend.c (ffffffff81961781)
Location: net/ipv4/fib_frontend.c:469
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c5f1b)
Location: net/ipv4/fib_frontend.c:473
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fcacb)
Location: net/ipv4/fib_frontend.c:474
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aeacc0)
Location: net/ipv4/fib_frontend.c:466
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81aeacc0-ffffffff81aeb001: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af7b80)
Location: net/ipv4/fib_frontend.c:466
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81af7b80-ffffffff81af7ed6: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae3290)
Location: net/ipv4/fib_frontend.c:468
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81ae3290-ffffffff81ae35e6: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba2b90)
Location: net/ipv4/fib_frontend.c:468
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81ba2b90-ffffffff81ba2ee6: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d352f0)
Location: net/ipv4/fib_frontend.c:471
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81d352f0-ffffffff81d356af: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efd860)
Location: net/ipv4/fib_frontend.c:471
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81efd860-ffffffff81efdc1f: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5d2d0)
Location: net/ipv4/fib_frontend.c:471
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff81f5d2d0-ffffffff81f5d6a5: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff82023860)
Location: net/ipv4/fib_frontend.c:471
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffff82023860-ffffffff82023c64: rtentry_to_fib_config (STB_LOCAL)
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
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb41d8)
Location: net/ipv4/fib_frontend.c:474
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffff800010cb41d8-ffff800010cb452c: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dbf548)
Location: net/ipv4/fib_frontend.c:474
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
c0dbf548-c0dbfa0c: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcc2bc)
Location: net/ipv4/fib_frontend.c:474
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtentry_to_fib_config(struct net *net, int cmd, struct rtentry *rt, struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080bf00)
Location: net/ipv4/fib_frontend.c:474
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
**Symbols:**

```
ffffffe00080bf00-ffffffe00080c22e: rtentry_to_fib_config (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199c86b)
Location: net/ipv4/fib_frontend.c:474
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8195632b)
Location: net/ipv4/fib_frontend.c:474
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a0710b)
Location: net/ipv4/fib_frontend.c:474
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a117db)
Location: net/ipv4/fib_frontend.c:474
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
