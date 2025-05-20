# Function: <code>skb_flow_dissect_ct</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f4d20)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffffffff818f4d20-ffffffff818f4d93: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81926bf0)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffffffff81926bf0-ffffffff81926c63: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fab80)
Location: net/core/flow_dissector.c:237
Inline: True
```
**Symbols:**

```
ffffffff819fab80-ffffffff819fabf3: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fa790)
Location: net/core/flow_dissector.c:237
Inline: True
```
**Symbols:**

```
ffffffff819fa790-ffffffff819fa803: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize, bool post_ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e0970)
Location: net/core/flow_dissector.c:238
Inline: True
```
**Symbols:**

```
ffffffff819e0970-ffffffff819e0a00: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize, bool post_ct, u16 zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a90ce0)
Location: net/core/flow_dissector.c:238
Inline: True
```
**Symbols:**

```
ffffffff81a90ce0-ffffffff81a90d79: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize, bool post_ct, u16 zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c06860)
Location: net/core/flow_dissector.c:240
Inline: False
```
**Symbols:**

```
ffffffff81c06860-ffffffff81c06928: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize, bool post_ct, u16 zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db6400)
Location: net/core/flow_dissector.c:264
Inline: False
```
**Symbols:**

```
ffffffff81db6400-ffffffff81db64c8: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize, bool post_ct, u16 zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e267b0)
Location: net/core/flow_dissector.c:274
Inline: False
```
**Symbols:**

```
ffffffff81e267b0-ffffffff81e26878: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize, bool post_ct, u16 zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee4740)
Location: net/core/flow_dissector.c:318
Inline: False
```
**Symbols:**

```
ffffffff81ee4740-ffffffff81ee4809: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc2f48)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffff800010bc2f48-ffff800010bc2fec: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c0cde294)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
c0cde294-c0cde334: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9d030)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
c000000000c9d030-c000000000c9d0b4: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe00074fcc8)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffffffe00074fcc8-ffffffe00074fd54: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c6bf0)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffffffff818c6bf0-ffffffff818c6c63: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81880b30)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffffffff81880b30-ffffffff81880ba3: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81917bf0)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffffffff81917bf0-ffffffff81917c63: skb_flow_dissect_ct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void skb_flow_dissect_ct(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container, u16 *ctinfo_map, size_t mapsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81938e00)
Location: net/core/flow_dissector.c:239
Inline: True
```
**Symbols:**

```
ffffffff81938e00-ffffffff81938e73: skb_flow_dissect_ct (STB_GLOBAL)
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
<b>Param added. </b>
<code>bool post_ct</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 zone</code>
</li>
</ul>
</details>
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
