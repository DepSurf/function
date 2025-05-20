# Function: <code>skb_flow_dissect_hash</code>

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
void skb_flow_dissect_hash(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fa2c0)
Location: net/core/flow_dissector.c:386
Inline: False
```
**Symbols:**

```
ffffffff819fa2c0-ffffffff819fa2e0: skb_flow_dissect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_flow_dissect_hash(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e04a0)
Location: net/core/flow_dissector.c:392
Inline: False
```
**Symbols:**

```
ffffffff819e04a0-ffffffff819e04c0: skb_flow_dissect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_flow_dissect_hash(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a90880)
Location: net/core/flow_dissector.c:393
Inline: False
```
**Symbols:**

```
ffffffff81a90880-ffffffff81a908a0: skb_flow_dissect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_flow_dissect_hash(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c067e0)
Location: net/core/flow_dissector.c:395
Inline: False
```
**Symbols:**

```
ffffffff81c067e0-ffffffff81c0680e: skb_flow_dissect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_flow_dissect_hash(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db6180)
Location: net/core/flow_dissector.c:419
Inline: False
```
**Symbols:**

```
ffffffff81db6180-ffffffff81db61ae: skb_flow_dissect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_flow_dissect_hash(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e26710)
Location: net/core/flow_dissector.c:429
Inline: False
```
**Symbols:**

```
ffffffff81e26710-ffffffff81e2673e: skb_flow_dissect_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_flow_dissect_hash(const struct sk_buff *skb, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee46a0)
Location: net/core/flow_dissector.c:473
Inline: False
```
**Symbols:**

```
ffffffff81ee46a0-ffffffff81ee46cf: skb_flow_dissect_hash (STB_GLOBAL)
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
