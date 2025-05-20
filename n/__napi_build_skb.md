# Function: <code>__napi_build_skb</code>

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
struct sk_buff *__napi_build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819cff20)
Location: net/core/skbuff.c:300
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:napi_build_skb
```
**Symbols:**

```
ffffffff819cff20-ffffffff819cff89: __napi_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__napi_build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7f950)
Location: net/core/skbuff.c:302
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:napi_build_skb
```
**Symbols:**

```
ffffffff81a7f950-ffffffff81a7f9b9: __napi_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__napi_build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3df0)
Location: net/core/skbuff.c:300
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:napi_build_skb
```
**Symbols:**

```
ffffffff81bf3df0-ffffffff81bf3e63: __napi_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__napi_build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da41a0)
Location: net/core/skbuff.c:438
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:napi_build_skb
```
**Symbols:**

```
ffffffff81da41a0-ffffffff81da4213: __napi_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__napi_build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e12e10)
Location: net/core/skbuff.c:505
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:napi_build_skb
```
**Symbols:**

```
ffffffff81e12e10-ffffffff81e12e83: __napi_build_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__napi_build_skb(void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecffd0)
Location: net/core/skbuff.c:506
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:napi_build_skb
```
**Symbols:**

```
ffffffff81ecffd0-ffffffff81ed0043: __napi_build_skb (STB_LOCAL)
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
