# Function: <code>rtmsg_to_fib6_config</code>

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
In net/ipv6/route.c (ffffffff817d8351)
Location: net/ipv6/route.c:2379
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff81846bb3)
Location: net/ipv6/route.c:2450
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff81878993)
Location: net/ipv6/route.c:2499
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff8189dc2d)
Location: net/ipv6/route.c:2583
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff8192027d)
Location: net/ipv6/route.c:3284
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff819784da)
Location: net/ipv6/route.c:3627
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff819ae0ca)
Location: net/ipv6/route.c:3607
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff81a1bee2)
Location: net/ipv6/route.c:4258
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff81a52b62)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rtmsg_to_fib6_config(struct net *net, struct in6_rtmsg *rtmsg, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b405e0)
Location: net/ipv6/route.c:4324
Inline: False
Direct callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81b405e0-ffffffff81b406f3: rtmsg_to_fib6_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rtmsg_to_fib6_config(struct net *net, struct in6_rtmsg *rtmsg, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4f0a0)
Location: net/ipv6/route.c:4308
Inline: False
Direct callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
**Symbols:**

```
ffffffff81b4f0a0-ffffffff81b4f1b3: rtmsg_to_fib6_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46d1e)
Location: net/ipv6/route.c:4323
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0df6e)
Location: net/ipv6/route.c:4453
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da8fa7)
Location: net/ipv6/route.c:4429
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f786b7)
Location: net/ipv6/route.c:4429
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd88a7)
Location: net/ipv6/route.c:4427
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a6227)
Location: net/ipv6/route.c:4429
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d16b4c)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1c7b8)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (c000000000e442d4)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085bdee)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff819f21f2)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff819aefb2)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff81a5cc72)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
In net/ipv6/route.c (ffffffff81a69042)
Location: net/ipv6/route.c:4271
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
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
</ul>
