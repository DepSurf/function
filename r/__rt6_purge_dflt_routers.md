# Function: <code>__rt6_purge_dflt_routers</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8187887f)
Location: net/ipv6/route.c:2460
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (ffffffff8189daf2)
Location: net/ipv6/route.c:2544
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (ffffffff81920176)
Location: net/ipv6/route.c:3242
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3584
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:3564
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4215
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rt6_purge_dflt_routers(struct net *net, struct fib6_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b49bc0)
Location: net/ipv6/route.c:4281
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
```
**Symbols:**

```
ffffffff81b49bc0-ffffffff81b49cd8: __rt6_purge_dflt_routers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rt6_purge_dflt_routers(struct net *net, struct fib6_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b587e0)
Location: net/ipv6/route.c:4265
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
```
**Symbols:**

```
ffffffff81b587e0-ffffffff81b58904: __rt6_purge_dflt_routers (STB_LOCAL)
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4280
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4410
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4386
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4386
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4384
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4386
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (ffffffe00085bc9a)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
