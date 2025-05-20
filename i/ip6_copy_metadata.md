# Function: <code>ip6_copy_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c4ac0)
Location: net/ipv6/ip6_output.c:542
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff817c4ac0-ffffffff817c4c1d: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81831b90)
Location: net/ipv6/ip6_output.c:541
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81831b90-ffffffff81831cdf: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818635c0)
Location: net/ipv6/ip6_output.c:567
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff818635c0-ffffffff8186370f: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81888a20)
Location: net/ipv6/ip6_output.c:568
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81888a20-ffffffff81888b57: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81909bb0)
Location: net/ipv6/ip6_output.c:587
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81909bb0-ffffffff81909d2f: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81960ee0)
Location: net/ipv6/ip6_output.c:561
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81960ee0-ffffffff81961095: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81995790)
Location: net/ipv6/ip6_output.c:569
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
**Symbols:**

```
ffffffff81995790-ffffffff8199594c: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81a01050-ffffffff81a011e7: ip6_copy_metadata (STB_LOCAL)
ffffffff81a04d6c-ffffffff81a04d76: ip6_copy_metadata.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a37c30)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81a37c30-ffffffff81a37dc8: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2dc10)
Location: net/ipv6/ip6_output.c:580
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81b2dc10-ffffffff81b2dddb: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3c660)
Location: net/ipv6/ip6_output.c:617
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81b3c660-ffffffff81b3c82b: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b29ac0)
Location: net/ipv6/ip6_output.c:648
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81b29ac0-ffffffff81b29c8b: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81bef650)
Location: net/ipv6/ip6_output.c:629
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81bef650-ffffffff81bef85f: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d88130)
Location: net/ipv6/ip6_output.c:651
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81d88130-ffffffff81d883c1: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f55ee0)
Location: net/ipv6/ip6_output.c:664
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81f55ee0-ffffffff81f56171: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb58b0)
Location: net/ipv6/ip6_output.c:665
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81fb58b0-ffffffff81fb5b5a: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82082f80)
Location: net/ipv6/ip6_output.c:675
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff82082f80-ffffffff8208322a: ip6_copy_metadata (STB_LOCAL)
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
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cf83a8)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffff800010cf83a8-ffff800010cf859c: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0dffae8)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
c0dffae8-c0dffcb4: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e20370)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
c000000000e20370-c000000000e20560: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe0008441ba)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffe0008441ba-ffffffe000844306: ip6_copy_metadata (STB_LOCAL)
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
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d72c0)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff819d72c0-ffffffff819d7458: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994080)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81994080-ffffffff81994218: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a41d40)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81a41d40-ffffffff81a41ed8: ip6_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4d9d0)
Location: net/ipv6/ip6_output.c:579
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
```
**Symbols:**

```
ffffffff81a4d9d0-ffffffff81a4db68: ip6_copy_metadata (STB_LOCAL)
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
