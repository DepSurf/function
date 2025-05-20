# Function: <code>__skb_flow_dissect_gre</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c4b22)
Location: net/core/flow_dissector.c:225
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183e56d)
Location: net/core/flow_dissector.c:318
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8188989c)
Location: net/core/flow_dissector.c:320
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818aa768)
Location: net/core/flow_dissector.c:390
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f6120)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff81927ffa)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fb100)
Location: net/core/flow_dissector.c:500
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819fb100-ffffffff819fb3fe: __skb_flow_dissect_gre (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fad00)
Location: net/core/flow_dissector.c:517
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819fad00-ffffffff819faff2: __skb_flow_dissect_gre (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e0f10)
Location: net/core/flow_dissector.c:524
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819e0f10-ffffffff819e121b: __skb_flow_dissect_gre (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a91350)
Location: net/core/flow_dissector.c:525
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81a91350-ffffffff81a9165b: __skb_flow_dissect_gre (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c07450)
Location: net/core/flow_dissector.c:527
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81c07450-ffffffff81c077dc: __skb_flow_dissect_gre (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db6ec0)
Location: net/core/flow_dissector.c:551
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81db6ec0-ffffffff81db724c: __skb_flow_dissect_gre (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e27580)
Location: net/core/flow_dissector.c:585
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81e27580-ffffffff81e2790c: __skb_flow_dissect_gre (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff *skb, struct flow_dissector_key_control *key_control, struct flow_dissector *flow_dissector, void *target_container, const void *data, __be16 *p_proto, int *p_nhoff, int *p_hlen, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee5370)
Location: net/core/flow_dissector.c:629
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81ee5370-ffffffff81ee56fc: __skb_flow_dissect_gre (STB_LOCAL)
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
In net/core/flow_dissector.c (ffff800010bc424c)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (c0cdf5e8)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (c000000000c9e4d8)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffe000750a56)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff818c7ffa)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff81881f3a)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff81918ffa)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff8193a1d4)
Location: net/core/flow_dissector.c:490
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
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
