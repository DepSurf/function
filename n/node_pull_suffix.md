# Function: <code>node_pull_suffix</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183d3f0)
Location: net/ipv4/fib_trie.c:1011
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8183d3f0-ffffffff8183d441: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8185ece0)
Location: net/ipv4/fib_trie.c:916
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8185ece0-ffffffff8185ed2c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818ded40)
Location: net/ipv4/fib_trie.c:917
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff818ded40-ffffffff818ded8c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81935850)
Location: net/ipv4/fib_trie.c:918
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81935850-ffffffff8193589c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81965250)
Location: net/ipv4/fib_trie.c:918
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81965250-ffffffff8196529c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cb200)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff819cb200-ffffffff819cb24c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a01d50)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81a01d50-ffffffff81a01d9c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af30cd)
Location: net/ipv4/fib_trie.c:911
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81afffdd)
Location: net/ipv4/fib_trie.c:911
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aeb660)
Location: net/ipv4/fib_trie.c:911
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81baafb0)
Location: net/ipv4/fib_trie.c:911
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3dd51)
Location: net/ipv4/fib_trie.c:912
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f07021)
Location: net/ipv4/fib_trie.c:912
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f66ae1)
Location: net/ipv4/fib_trie.c:912
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202d0b1)
Location: net/ipv4/fib_trie.c:913
Inline: True
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
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cba430)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffff800010cba430-ffff800010cba4a8: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc5c88)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
c0dc5c88-c0dc5cec: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd38e0)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
c000000000dd38e0-c000000000dd397c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe000810d28)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffe000810d28-ffffffe000810d86: node_pull_suffix (STB_LOCAL)
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
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a1af0)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff819a1af0-ffffffff819a1b3c: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195b5b0)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff8195b5b0-ffffffff8195b5fc: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0c390)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81a0c390-ffffffff81a0c3dc: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void node_pull_suffix(struct key_vector *tn, unsigned char slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a16b80)
Location: net/ipv4/fib_trie.c:914
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
```
**Symbols:**

```
ffffffff81a16b80-ffffffff81a16bcc: node_pull_suffix (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
