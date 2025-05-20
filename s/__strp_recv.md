# Function: <code>__strp_recv</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff8195ae80)
Location: net/strparser/strparser.c:100
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff8195ae80-ffffffff8195b523: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819b4520)
Location: net/strparser/strparser.c:99
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff819b4520-ffffffff819b4be5: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819eb550)
Location: net/strparser/strparser.c:99
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff819eb550-ffffffff819ebbe4: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/strparser/strparser.c (0)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81a5a730-ffffffff81a5ad2a: __strp_recv (STB_LOCAL)
ffffffff81a5ada8-ffffffff81a5adec: __strp_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a91380)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81a91380-ffffffff81a91993: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8c7f0)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81b8c7f0-ffffffff81b8ce20: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b9c440)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81b9c440-ffffffff81b9ca70: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8b500)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81b8b500-ffffffff81b8bb30: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81c577a0)
Location: net/strparser/strparser.c:89
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81c577a0-ffffffff81c57dd0: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81df8dd0)
Location: net/strparser/strparser.c:89
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81df8dd0-ffffffff81df9463: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81fcd3c0)
Location: net/strparser/strparser.c:89
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81fcd3c0-ffffffff81fcda4c: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff82048cf0)
Location: net/strparser/strparser.c:89
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff82048cf0-ffffffff82049378: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff8211b070)
Location: net/strparser/strparser.c:89
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff8211b070-ffffffff8211b6f8: __strp_recv (STB_LOCAL)
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
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffff800010d5ef48)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffff800010d5ef48-ffff800010d5f4fc: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c0e5eb34)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
c0e5eb34-c0e5f138: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c000000000e999a0)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
c000000000e999a0-c000000000e9a118: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffe0008946d4)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffe0008946d4-ffffffe000894bb2: __strp_recv (STB_LOCAL)
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
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a30a10)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81a30a10-ffffffff81a31023: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819edc00)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff819edc00-ffffffff819ee213: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a9c5c0)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81a9c5c0-ffffffff81a9cbd3: __strp_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t *desc, struct sk_buff *orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81aa87a0)
Location: net/strparser/strparser.c:97
Inline: False
Direct callers:
  - net/strparser/strparser.c:strp_recv
  - net/strparser/strparser.c:strp_process
```
**Symbols:**

```
ffffffff81aa87a0-ffffffff81aa8db3: __strp_recv (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
