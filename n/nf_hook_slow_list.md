# Function: <code>nf_hook_slow_list</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8dca0)
Location: net/netfilter/core.c:539
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81a8dca0-ffffffff81a8dd89: nf_hook_slow_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97c70)
Location: net/netfilter/core.c:616
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81a97c70-ffffffff81a97d59: nf_hook_slow_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a82fc0)
Location: net/netfilter/core.c:616
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81a82fc0-ffffffff81a830a9: nf_hook_slow_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3cc50)
Location: net/netfilter/core.c:617
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81b3cc50-ffffffff81b3cd39: nf_hook_slow_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc9100)
Location: net/netfilter/core.c:648
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81cc9100-ffffffff81cc91ed: nf_hook_slow_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e88c90)
Location: net/netfilter/core.c:642
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81e88c90-ffffffff81e88d7d: nf_hook_slow_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee6c00)
Location: net/netfilter/core.c:654
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81ee6c00-ffffffff81ee6ced: nf_hook_slow_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nf_hook_slow_list(struct list_head *head, struct nf_hook_state *state, const struct nf_hook_entries *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81faaa10)
Location: net/netfilter/core.c:654
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81faaa10-ffffffff81faaafd: nf_hook_slow_list (STB_GLOBAL)
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
