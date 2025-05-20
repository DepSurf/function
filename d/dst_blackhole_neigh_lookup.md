# Function: <code>dst_blackhole_neigh_lookup</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct neighbour *dst_blackhole_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a10b00)
Location: net/core/dst.c:250
Inline: False
```
**Symbols:**

```
ffffffff81a10b00-ffffffff81a10b0d: dst_blackhole_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct neighbour *dst_blackhole_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff819f7970)
Location: net/core/dst.c:250
Inline: False
```
**Symbols:**

```
ffffffff819f7970-ffffffff819f797d: dst_blackhole_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct neighbour *dst_blackhole_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81aa9560)
Location: net/core/dst.c:248
Inline: False
```
**Symbols:**

```
ffffffff81aa9560-ffffffff81aa956d: dst_blackhole_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct neighbour *dst_blackhole_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81c218f0)
Location: net/core/dst.c:248
Inline: False
```
**Symbols:**

```
ffffffff81c218f0-ffffffff81c21901: dst_blackhole_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct neighbour *dst_blackhole_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81dd3ae0)
Location: net/core/dst.c:248
Inline: False
```
**Symbols:**

```
ffffffff81dd3ae0-ffffffff81dd3af1: dst_blackhole_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct neighbour *dst_blackhole_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e448a0)
Location: net/core/dst.c:229
Inline: False
```
**Symbols:**

```
ffffffff81e448a0-ffffffff81e448b1: dst_blackhole_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct neighbour *dst_blackhole_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f03500)
Location: net/core/dst.c:229
Inline: False
```
**Symbols:**

```
ffffffff81f03500-ffffffff81f03511: dst_blackhole_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
