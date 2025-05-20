# Function: <code>ptp_parse_header</code>

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
struct ptp_header *ptp_parse_header(struct sk_buff *skb, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ptp_classifier.c (ffffffff81a51110)
Location: net/core/ptp_classifier.c:110
Inline: False
```
**Symbols:**

```
ffffffff81a51110-ffffffff81a51183: ptp_parse_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ptp_header *ptp_parse_header(struct sk_buff *skb, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ptp_classifier.c (ffffffff81a36990)
Location: net/core/ptp_classifier.c:110
Inline: False
```
**Symbols:**

```
ffffffff81a36990-ffffffff81a36a00: ptp_parse_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ptp_header *ptp_parse_header(struct sk_buff *skb, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ptp_classifier.c (ffffffff81aec6e0)
Location: net/core/ptp_classifier.c:110
Inline: False
```
**Symbols:**

```
ffffffff81aec6e0-ffffffff81aec750: ptp_parse_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ptp_header *ptp_parse_header(struct sk_buff *skb, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ptp_classifier.c (ffffffff81c6f215)
Location: net/core/ptp_classifier.c:110
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
**Symbols:**

```
ffffffff81c6f0e0-ffffffff81c6f169: ptp_parse_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ptp_header *ptp_parse_header(struct sk_buff *skb, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ptp_classifier.c (ffffffff81e26fe5)
Location: net/core/ptp_classifier.c:110
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
**Symbols:**

```
ffffffff81e26e90-ffffffff81e26f19: ptp_parse_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ptp_header *ptp_parse_header(struct sk_buff *skb, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ptp_classifier.c (ffffffff81e9c565)
Location: net/core/ptp_classifier.c:110
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
**Symbols:**

```
ffffffff81e9c430-ffffffff81e9c4a8: ptp_parse_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ptp_header *ptp_parse_header(struct sk_buff *skb, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/ptp_classifier.c (ffffffff81f5ecf5)
Location: net/core/ptp_classifier.c:110
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_msg_is_sync
```
**Symbols:**

```
ffffffff81f5ebc0-ffffffff81f5ec38: ptp_parse_header (STB_GLOBAL)
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
