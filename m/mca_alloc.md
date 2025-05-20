# Function: <code>mca_alloc</code>

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
In net/ipv6/mcast.c (ffffffff817ebcfd)
Location: net/ipv6/mcast.c:820
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff8185a531)
Location: net/ipv6/mcast.c:820
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff8188c479)
Location: net/ipv6/mcast.c:833
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff818b2b5b)
Location: net/ipv6/mcast.c:833
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff819358c4)
Location: net/ipv6/mcast.c:833
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff8198e227)
Location: net/ipv6/mcast.c:853
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff819c4b1a)
Location: net/ipv6/mcast.c:853
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81a3396d)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81a6a4bd)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ifmcaddr6 *mca_alloc(struct inet6_dev *idev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b60960)
Location: net/ipv6/mcast.c:847
Inline: False
Direct callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
**Symbols:**

```
ffffffff81b60960-ffffffff81b60a4d: mca_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ifmcaddr6 *mca_alloc(struct inet6_dev *idev, const struct in6_addr *addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b6f0d0)
Location: net/ipv6/mcast.c:847
Inline: False
Direct callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
**Symbols:**

```
ffffffff81b6f0d0-ffffffff81b6f1bd: mca_alloc (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81b5ffd4)
Location: net/ipv6/mcast.c:869
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81c278a6)
Location: net/ipv6/mcast.c:874
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81dc4c2e)
Location: net/ipv6/mcast.c:874
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81f9577e)
Location: net/ipv6/mcast.c:874
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81ff612e)
Location: net/ipv6/mcast.c:874
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff820c3d3e)
Location: net/ipv6/mcast.c:874
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffff800010d31538)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (c0e348fc)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (c000000000e63b40)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffe00086fde4)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81a09b4d)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff819c690d)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81a745cd)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
In net/ipv6/mcast.c (ffffffff81a80c72)
Location: net/ipv6/mcast.c:850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
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
