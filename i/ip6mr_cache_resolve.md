# Function: <code>ip6mr_cache_resolve</code>

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
In net/ipv6/ip6mr.c (ffffffff817fb002)
Location: net/ipv6/ip6mr.c:1095
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In net/ipv6/ip6mr.c (ffffffff8186a84f)
Location: net/ipv6/ip6mr.c:1097
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In net/ipv6/ip6mr.c (ffffffff8189d69f)
Location: net/ipv6/ip6mr.c:1097
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In net/ipv6/ip6mr.c (ffffffff818c3c11)
Location: net/ipv6/ip6mr.c:1100
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In net/ipv6/ip6mr.c (ffffffff81946eaa)
Location: net/ipv6/ip6mr.c:1100
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:991
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1005
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6mr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc6_cache *uc, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b76490)
Location: net/ipv6/ip6mr.c:1004
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81b76490-ffffffff81b765ce: ip6mr_cache_resolve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6mr_cache_resolve(struct net *net, struct mr_table *mrt, struct mfc6_cache *uc, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b85250)
Location: net/ipv6/ip6mr.c:1004
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81b85250-ffffffff81b8538e: ip6mr_cache_resolve (STB_LOCAL)
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1004
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1005
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:999
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1007
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1007
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1007
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (ffffffe000880bb6)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1000
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
