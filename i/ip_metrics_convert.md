# Function: <code>ip_metrics_convert</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/metrics.c (ffffffff8193c920)
Location: net/ipv4/metrics.c:8
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8193c920-ffffffff8193ca8e: ip_metrics_convert (STB_GLOBAL)
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
In net/ipv4/metrics.c (ffffffff8196c673)
Location: net/ipv4/metrics.c:8
Inline: True
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
In net/ipv4/metrics.c (ffffffff819d3393)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (ffffffff81a09f03)
Location: net/ipv4/metrics.c:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/metrics.c (ffffffff81afa610)
Location: net/ipv4/metrics.c:9
Inline: False
```
**Symbols:**

```
ffffffff81afa610-ffffffff81afa7bf: ip_metrics_convert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/metrics.c (ffffffff81b07dc0)
Location: net/ipv4/metrics.c:9
Inline: False
```
**Symbols:**

```
ffffffff81b07dc0-ffffffff81b07f77: ip_metrics_convert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/metrics.c (ffffffff81af35d0)
Location: net/ipv4/metrics.c:9
Inline: False
```
**Symbols:**

```
ffffffff81af35d0-ffffffff81af37d7: ip_metrics_convert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/metrics.c (0)
Location: net/ipv4/metrics.c:9
Inline: False
```
**Symbols:**

```
ffffffff81bb3ae0-ffffffff81bb3cfe: ip_metrics_convert (STB_LOCAL)
ffffffff81d3dc12-ffffffff81d3dc2e: ip_metrics_convert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/metrics.c (0)
Location: net/ipv4/metrics.c:9
Inline: False
```
**Symbols:**

```
ffffffff81d47320-ffffffff81d4755d: ip_metrics_convert (STB_LOCAL)
ffffffff81f0a4cd-ffffffff81f0a4e9: ip_metrics_convert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/metrics.c (0)
Location: net/ipv4/metrics.c:10
Inline: False
```
**Symbols:**

```
ffffffff81f10780-ffffffff81f109c5: ip_metrics_convert (STB_LOCAL)
ffffffff820b1d8a-ffffffff820b1d9e: ip_metrics_convert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/metrics.c (0)
Location: net/ipv4/metrics.c:10
Inline: False
```
**Symbols:**

```
ffffffff81f70470-ffffffff81f706b5: ip_metrics_convert (STB_LOCAL)
ffffffff82132f97-ffffffff82132fab: ip_metrics_convert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip_metrics_convert(struct net *net, struct nlattr *fc_mx, int fc_mx_len, u32 *metrics, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/metrics.c (0)
Location: net/ipv4/metrics.c:10
Inline: False
```
**Symbols:**

```
ffffffff82036ba0-ffffffff82036de5: ip_metrics_convert (STB_LOCAL)
ffffffff82214946-ffffffff8221495a: ip_metrics_convert.cold (STB_LOCAL)
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
In net/ipv4/metrics.c (ffff800010cc327c)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (c0dceaa0)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (c000000000ddee14)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (ffffffe00081863e)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (ffffffff819a9ca3)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (ffffffff81963763)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (ffffffff81a14543)
Location: net/ipv4/metrics.c:9
Inline: True
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
In net/ipv4/metrics.c (ffffffff81a1ef53)
Location: net/ipv4/metrics.c:9
Inline: True
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
