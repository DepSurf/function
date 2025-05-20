# Function: <code>napi_skb_cache_put</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d8485)
Location: net/core/skbuff.c:915
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
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
In net/core/skbuff.c (ffffffff81a882b8)
Location: net/core/skbuff.c:931
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
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
In net/core/skbuff.c (ffffffff81bfd908)
Location: net/core/skbuff.c:936
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
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
In net/core/skbuff.c (ffffffff81dae638)
Location: net/core/skbuff.c:1117
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__kfree_skb_defer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void napi_skb_cache_put(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1e4dc)
Location: net/core/skbuff.c:1257
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
Direct callers:
  - net/core/skbuff.c:__napi_kfree_skb
```
**Symbols:**

```
ffffffff81e10460-ffffffff81e10523: napi_skb_cache_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void napi_skb_cache_put(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eccf70)
Location: net/core/skbuff.c:1343
Inline: False
Direct callers:
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:__napi_kfree_skb
```
**Symbols:**

```
ffffffff81eccf70-ffffffff81ecd043: napi_skb_cache_put (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
