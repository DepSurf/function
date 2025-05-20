# Function: <code>bpf_skb_check_mtu</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_check_mtu(u64 skb, u64 ifindex, u64 mtu_len, u64 len_diff, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a12220)
Location: net/core/filter.c:5595
Inline: False
```
**Symbols:**

```
ffffffff81a12220-ffffffff81a1231d: bpf_skb_check_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_check_mtu(u64 skb, u64 ifindex, u64 mtu_len, u64 len_diff, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac2ef0)
Location: net/core/filter.c:5719
Inline: False
```
**Symbols:**

```
ffffffff81ac2ef0-ffffffff81ac2fed: bpf_skb_check_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_check_mtu(u64 skb, u64 ifindex, u64 mtu_len, u64 len_diff, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3dc20)
Location: net/core/filter.c:6028
Inline: False
```
**Symbols:**

```
ffffffff81c3dc20-ffffffff81c3dd30: bpf_skb_check_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_check_mtu(u64 skb, u64 ifindex, u64 mtu_len, u64 len_diff, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df1d70)
Location: net/core/filter.c:6042
Inline: False
```
**Symbols:**

```
ffffffff81df1d70-ffffffff81df1e80: bpf_skb_check_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_check_mtu(u64 skb, u64 ifindex, u64 mtu_len, u64 len_diff, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e63d00)
Location: net/core/filter.c:6121
Inline: False
```
**Symbols:**

```
ffffffff81e63d00-ffffffff81e63e10: bpf_skb_check_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_check_mtu(u64 skb, u64 ifindex, u64 mtu_len, u64 len_diff, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f22ee0)
Location: net/core/filter.c:6211
Inline: False
```
**Symbols:**

```
ffffffff81f22ee0-ffffffff81f22fed: bpf_skb_check_mtu (STB_GLOBAL)
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
