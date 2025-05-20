# Function: <code>__build_skb_around</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e58b0)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff818e58b0-ffffffff818e596a: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917a00)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81917a00-ffffffff81917aba: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9f20)
Location: net/core/skbuff.c:262
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff819e9f20-ffffffff819e9fda: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9cc0)
Location: net/core/skbuff.c:265
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff819e9cc0-ffffffff819e9d7a: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819cfe00)
Location: net/core/skbuff.c:190
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff819cfe00-ffffffff819cfeb8: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7f830)
Location: net/core/skbuff.c:192
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81a7f830-ffffffff81a7f8e8: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3c90)
Location: net/core/skbuff.c:190
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81bf3c90-ffffffff81bf3d66: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:339
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81da4060-ffffffff81da4183: __build_skb_around (STB_LOCAL)
ffffffff820aabf0-ffffffff820aac05: __build_skb_around.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:410
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81e12cd0-ffffffff81e12df3: __build_skb_around (STB_LOCAL)
ffffffff8212c103-ffffffff8212c118: __build_skb_around.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:411
Inline: False
Direct callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81ecfe90-ffffffff81ecffb3: __build_skb_around (STB_LOCAL)
ffffffff8220dde3-ffffffff8220ddf8: __build_skb_around.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0de8)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffff800010bb0de8-ffff800010bb0e6c: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce13c)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
c0cce13c-c0cce1c0: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87140)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
c000000000c87140-c000000000c87204: __build_skb_around (STB_LOCAL)
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
In net/core/skbuff.c (ffffffe000741a46)
Location: net/core/skbuff.c:261
Inline: True
Inline callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7a00)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff818b7a00-ffffffff818b7aba: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871950)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81871950-ffffffff81871a0a: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908a00)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81908a00-ffffffff81908aba: __build_skb_around (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929ab0)
Location: net/core/skbuff.c:261
Inline: False
Direct callers:
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
```
**Symbols:**

```
ffffffff81929ab0-ffffffff81929b6a: __build_skb_around (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct sk_buff *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
