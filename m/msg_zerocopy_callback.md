# Function: <code>msg_zerocopy_callback</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void msg_zerocopy_callback(struct sk_buff *skb, struct ubuf_info *uarg, bool success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d5720)
Location: net/core/skbuff.c:1300
Inline: True
```
**Symbols:**

```
ffffffff819d5720-ffffffff819d5761: msg_zerocopy_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void msg_zerocopy_callback(struct sk_buff *skb, struct ubuf_info *uarg, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a851e0)
Location: net/core/skbuff.c:1321
Inline: False
```
**Symbols:**

```
ffffffff81a851e0-ffffffff81a853cc: msg_zerocopy_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void msg_zerocopy_callback(struct sk_buff *skb, struct ubuf_info *uarg, bool success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfb440)
Location: net/core/skbuff.c:1322
Inline: True
```
**Symbols:**

```
ffffffff81bfb440-ffffffff81bfb4a5: msg_zerocopy_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void msg_zerocopy_callback(struct sk_buff *skb, struct ubuf_info *uarg, bool success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81daa160)
Location: net/core/skbuff.c:1508
Inline: True
```
**Symbols:**

```
ffffffff81daa160-ffffffff81daa1c5: msg_zerocopy_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void msg_zerocopy_callback(struct sk_buff *skb, struct ubuf_info *uarg, bool success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18f00)
Location: net/core/skbuff.c:1652
Inline: True
```
**Symbols:**

```
ffffffff81e18f00-ffffffff81e18f65: msg_zerocopy_callback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void msg_zerocopy_callback(struct sk_buff *skb, struct ubuf_info *uarg, bool success);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed6390)
Location: net/core/skbuff.c:1740
Inline: True
```
**Symbols:**

```
ffffffff81ed6390-ffffffff81ed63f5: msg_zerocopy_callback (STB_GLOBAL)
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
