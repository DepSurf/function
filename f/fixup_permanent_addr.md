# Function: <code>fixup_permanent_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183f0ed)
Location: net/ipv6/addrconf.c:3247
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff81870cfa)
Location: net/ipv6/addrconf.c:3263
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff81895fde)
Location: net/ipv6/addrconf.c:3321
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff819173a8)
Location: net/ipv6/addrconf.c:3307
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff8196e630)
Location: net/ipv6/addrconf.c:3359
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff819a420d)
Location: net/ipv6/addrconf.c:3375
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff81a1057d)
Location: net/ipv6/addrconf.c:3413
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff81a472bd)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fixup_permanent_addr(struct net *net, struct inet6_dev *idev, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b39300)
Location: net/ipv6/addrconf.c:3384
Inline: False
```
**Symbols:**

```
ffffffff81b39300-ffffffff81b39420: fixup_permanent_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fixup_permanent_addr(struct net *net, struct inet6_dev *idev, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b48000)
Location: net/ipv6/addrconf.c:3411
Inline: False
```
**Symbols:**

```
ffffffff81b48000-ffffffff81b48120: fixup_permanent_addr (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81b360ac)
Location: net/ipv6/addrconf.c:3413
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81bfc823)
Location: net/ipv6/addrconf.c:3443
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_permanent_addr
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
In net/ipv6/addrconf.c (ffffffff81d9614f)
Location: net/ipv6/addrconf.c:3450
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_permanent_addr
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
In net/ipv6/addrconf.c (ffffffff81f64a0f)
Location: net/ipv6/addrconf.c:3474
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_permanent_addr
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
In net/ipv6/addrconf.c (ffffffff81fc4aff)
Location: net/ipv6/addrconf.c:3479
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_permanent_addr
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
In net/ipv6/addrconf.c (ffffffff820920af)
Location: net/ipv6/addrconf.c:3530
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_permanent_addr
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
In net/ipv6/addrconf.c (ffff800010d09df0)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (c0e104e8)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (c000000000e34884)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffe00085195c)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff819e694d)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff819a370d)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff81a513cd)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff81a5d31d)
Location: net/ipv6/addrconf.c:3419
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
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
