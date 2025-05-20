# Function: <code>ioam6_namespace</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ioam6_namespace *ioam6_namespace(struct net *net, __be16 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81c3a760)
Location: net/ipv6/ioam6.c:623
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff81c3a760-ffffffff81c3a885: ioam6_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ioam6_namespace *ioam6_namespace(struct net *net, __be16 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81dd8610)
Location: net/ipv6/ioam6.c:625
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff81dd8610-ffffffff81dd86f4: ioam6_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ioam6_namespace *ioam6_namespace(struct net *net, __be16 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81faa020)
Location: net/ipv6/ioam6.c:626
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff81faa020-ffffffff81faa104: ioam6_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ioam6_namespace *ioam6_namespace(struct net *net, __be16 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff8200a970)
Location: net/ipv6/ioam6.c:626
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff8200a970-ffffffff8200aa4a: ioam6_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ioam6_namespace *ioam6_namespace(struct net *net, __be16 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff820d9940)
Location: net/ipv6/ioam6.c:626
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff820d9940-ffffffff820d9a1a: ioam6_namespace (STB_GLOBAL)
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
