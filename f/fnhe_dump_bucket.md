# Function: <code>fnhe_dump_bucket</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2861
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fnhe_dump_bucket(struct net *net, struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fnhe_hash_bucket *bucket, int genid, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a91700)
Location: net/ipv4/route.c:2959
Inline: False
Direct callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81a91700-ffffffff81a91801: fnhe_dump_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fnhe_dump_bucket(struct net *net, struct sk_buff *skb, struct netlink_callback *cb, u32 table_id, struct fnhe_hash_bucket *bucket, int genid, int *fa_index, int fa_start, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9b580)
Location: net/ipv4/route.c:2941
Inline: False
Direct callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
```
**Symbols:**

```
ffffffff81a9b580-ffffffff81a9b681: fnhe_dump_bucket (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81a8c0c8)
Location: net/ipv4/route.c:2942
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (ffffffff81b4705c)
Location: net/ipv4/route.c:3060
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (ffffffff81cd412e)
Location: net/ipv4/route.c:3084
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (ffffffff81e9438e)
Location: net/ipv4/route.c:3075
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (ffffffff81ef2b5e)
Location: net/ipv4/route.c:3071
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (ffffffff81fb6aee)
Location: net/ipv4/route.c:3026
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (ffffffe0007c5f4e)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2872
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_dump_info_fnhe
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
