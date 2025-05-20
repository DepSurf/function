# Function: <code>dst_blackhole_update_pmtu</code>

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
void dst_blackhole_update_pmtu(struct dst_entry *dst, struct sock *sk, struct sk_buff *skb, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a10b10)
Location: net/core/dst.c:257
Inline: False
```
**Symbols:**

```
ffffffff81a10b10-ffffffff81a10b1b: dst_blackhole_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dst_blackhole_update_pmtu(struct dst_entry *dst, struct sock *sk, struct sk_buff *skb, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff819f7980)
Location: net/core/dst.c:257
Inline: False
```
**Symbols:**

```
ffffffff819f7980-ffffffff819f798b: dst_blackhole_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dst_blackhole_update_pmtu(struct dst_entry *dst, struct sock *sk, struct sk_buff *skb, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81aa9570)
Location: net/core/dst.c:255
Inline: False
```
**Symbols:**

```
ffffffff81aa9570-ffffffff81aa957b: dst_blackhole_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dst_blackhole_update_pmtu(struct dst_entry *dst, struct sock *sk, struct sk_buff *skb, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81c21910)
Location: net/core/dst.c:255
Inline: False
```
**Symbols:**

```
ffffffff81c21910-ffffffff81c2191f: dst_blackhole_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dst_blackhole_update_pmtu(struct dst_entry *dst, struct sock *sk, struct sk_buff *skb, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81dd3b10)
Location: net/core/dst.c:255
Inline: False
```
**Symbols:**

```
ffffffff81dd3b10-ffffffff81dd3b1f: dst_blackhole_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dst_blackhole_update_pmtu(struct dst_entry *dst, struct sock *sk, struct sk_buff *skb, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e448d0)
Location: net/core/dst.c:236
Inline: False
```
**Symbols:**

```
ffffffff81e448d0-ffffffff81e448df: dst_blackhole_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dst_blackhole_update_pmtu(struct dst_entry *dst, struct sock *sk, struct sk_buff *skb, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f03530)
Location: net/core/dst.c:236
Inline: False
```
**Symbols:**

```
ffffffff81f03530-ffffffff81f0353f: dst_blackhole_update_pmtu (STB_GLOBAL)
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
