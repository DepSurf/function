# Function: <code>ip_copy_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175c540)
Location: net/ipv4/ip_output.c:470
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff8175c540-ffffffff8175c6cc: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817c9340)
Location: net/ipv4/ip_output.c:468
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff817c9340-ffffffff817c94ba: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817f8ee0)
Location: net/ipv4/ip_output.c:512
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff817f8ee0-ffffffff817f905b: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81819300)
Location: net/ipv4/ip_output.c:516
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81819300-ffffffff8181946d: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818978c0)
Location: net/ipv4/ip_output.c:516
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff818978c0-ffffffff81897a79: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818ebbd0)
Location: net/ipv4/ip_output.c:516
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff818ebbd0-ffffffff818ebdbf: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81918ea0)
Location: net/ipv4/ip_output.c:517
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
```
**Symbols:**

```
ffffffff81918ea0-ffffffff81919096: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_output.c (0)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff8197afb0-ffffffff8197b179: ip_copy_metadata (STB_LOCAL)
ffffffff8197eb27-ffffffff8197eb3a: ip_copy_metadata.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b1920)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff819b1920-ffffffff819b1af0: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9c170)
Location: net/ipv4/ip_output.c:543
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81a9c170-ffffffff81a9c377: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa5fd0)
Location: net/ipv4/ip_output.c:550
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81aa5fd0-ffffffff81aa61d7: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a91190)
Location: net/ipv4/ip_output.c:551
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81a91190-ffffffff81a91397: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4c500)
Location: net/ipv4/ip_output.c:550
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81b4c500-ffffffff81b4c750: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cd9b50)
Location: net/ipv4/ip_output.c:550
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81cd9b50-ffffffff81cd9e10: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9a2e0)
Location: net/ipv4/ip_output.c:550
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81e9a2e0-ffffffff81e9a5a0: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81ef8c40)
Location: net/ipv4/ip_output.c:552
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81ef8c40-ffffffff81ef8f15: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fbcb60)
Location: net/ipv4/ip_output.c:553
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81fbcb60-ffffffff81fbce35: ip_copy_metadata (STB_LOCAL)
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
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c622f8)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffff800010c622f8-ffff800010c624f4: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d71ad8)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
c0d71ad8-c0d71cd0: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d655a0)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
c000000000d655a0-c000000000d657b0: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007c9ebc)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffe0007c9ebc-ffffffe0007ca032: ip_copy_metadata (STB_LOCAL)
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
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81951790)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff81951790-ffffffff81951960: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190b280)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff8190b280-ffffffff8190b450: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bbf60)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff819bbf60-ffffffff819bc130: ip_copy_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_copy_metadata(struct sk_buff *to, struct sk_buff *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c5870)
Location: net/ipv4/ip_output.c:544
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
```
**Symbols:**

```
ffffffff819c5870-ffffffff819c5a40: ip_copy_metadata (STB_LOCAL)
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
