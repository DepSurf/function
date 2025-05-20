# Function: <code>flow_hash_from_keys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81711680)
Location: net/core/flow_dissector.c:622
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/core/flow_dissector.c:__get_hash_from_flowi4
```
**Symbols:**

```
ffffffff81711680-ffffffff81711913: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81778fc0)
Location: net/core/flow_dissector.c:611
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi4
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
```
**Symbols:**

```
ffffffff81778fc0-ffffffff81779264: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817a6110)
Location: net/core/flow_dissector.c:716
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi4
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
```
**Symbols:**

```
ffffffff817a6110-ffffffff817a63b4: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c4300)
Location: net/core/flow_dissector.c:911
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi4
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/core/flow_dissector.c:__skb_get_hash_flowi4
  - net/core/flow_dissector.c:__skb_get_hash_flowi6
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff817c4300-ffffffff817c45a4: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183ddd0)
Location: net/core/flow_dissector.c:1110
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi4
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
```
**Symbols:**

```
ffffffff8183ddd0-ffffffff8183e074: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818886e0)
Location: net/core/flow_dissector.c:1165
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff818886e0-ffffffff8188895e: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818a92b0)
Location: net/core/flow_dissector.c:1341
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff818a92b0-ffffffff818a953e: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f4a20)
Location: net/core/flow_dissector.c:1454
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff818f4a20-ffffffff818f4c78: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819269d0)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff819269d0-ffffffff81926b4b: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fa9c0)
Location: net/core/flow_dissector.c:1509
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff819fa9c0-ffffffff819faa4d: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fa5d0)
Location: net/core/flow_dissector.c:1532
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff819fa5d0-ffffffff819fa65d: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e07c0)
Location: net/core/flow_dissector.c:1558
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff819e07c0-ffffffff819e084f: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a90a10)
Location: net/core/flow_dissector.c:1563
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81a90a10-ffffffff81a90bbe: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c06a70)
Location: net/core/flow_dissector.c:1617
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81c06a70-ffffffff81c06c53: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db6220)
Location: net/core/flow_dissector.c:1689
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81db6220-ffffffff81db63e6: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e26f40)
Location: net/core/flow_dissector.c:1729
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81e26f40-ffffffff81e27140: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee4ef0)
Location: net/core/flow_dissector.c:1780
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81ee4ef0-ffffffff81ee50f0: flow_hash_from_keys (STB_GLOBAL)
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
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc2cd8)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffff800010bc2cd8-ffff800010bc2ebc: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c0cde030)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
c0cde030-c0cde1dc: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9cd20)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
c000000000c9cd20-c000000000c9cf84: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe00074f9e8)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffe00074f9e8-ffffffe00074fb84: flow_hash_from_keys (STB_GLOBAL)
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
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c69d0)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff818c69d0-ffffffff818c6b4b: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81880910)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81880910-ffffffff81880a8b: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819179d0)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff819179d0-ffffffff81917b4b: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81938be0)
Location: net/core/flow_dissector.c:1490
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__get_hash_from_flowi6
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
**Symbols:**

```
ffffffff81938be0-ffffffff81938d5b: flow_hash_from_keys (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
