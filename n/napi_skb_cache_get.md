# Function: <code>napi_skb_cache_get</code>

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
struct sk_buff *napi_skb_cache_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819cfec0)
Location: net/core/skbuff.c:170
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
```
**Symbols:**

```
ffffffff819cfec0-ffffffff819cff1a: napi_skb_cache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *napi_skb_cache_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7f8f0)
Location: net/core/skbuff.c:172
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
```
**Symbols:**

```
ffffffff81a7f8f0-ffffffff81a7f94a: napi_skb_cache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *napi_skb_cache_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3d70)
Location: net/core/skbuff.c:170
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
```
**Symbols:**

```
ffffffff81bf3d70-ffffffff81bf3de2: napi_skb_cache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *napi_skb_cache_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1b20)
Location: net/core/skbuff.c:253
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
```
**Symbols:**

```
ffffffff81da1b20-ffffffff81da1b82: napi_skb_cache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *napi_skb_cache_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e102c0)
Location: net/core/skbuff.c:324
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
```
**Symbols:**

```
ffffffff81e102c0-ffffffff81e1033c: napi_skb_cache_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *napi_skb_cache_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eccdc0)
Location: net/core/skbuff.c:325
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
```
**Symbols:**

```
ffffffff81eccdc0-ffffffff81ecce4b: napi_skb_cache_get (STB_LOCAL)
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
