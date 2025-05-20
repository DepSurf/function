# Function: <code>ioam6_fill_trace_data</code>

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
void ioam6_fill_trace_data(struct sk_buff *skb, struct ioam6_namespace *ns, struct ioam6_trace_hdr *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81c3a890)
Location: net/ipv6/ioam6.c:847
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff81c3a890-ffffffff81c3a92d: ioam6_fill_trace_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ioam6_fill_trace_data(struct sk_buff *skb, struct ioam6_namespace *ns, struct ioam6_trace_hdr *trace, bool is_input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81dd8700)
Location: net/ipv6/ioam6.c:860
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff81dd8700-ffffffff81dd87ea: ioam6_fill_trace_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ioam6_fill_trace_data(struct sk_buff *skb, struct ioam6_namespace *ns, struct ioam6_trace_hdr *trace, bool is_input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff81faa120)
Location: net/ipv6/ioam6.c:861
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff81faa120-ffffffff81faa20a: ioam6_fill_trace_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ioam6_fill_trace_data(struct sk_buff *skb, struct ioam6_namespace *ns, struct ioam6_trace_hdr *trace, bool is_input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff8200aa60)
Location: net/ipv6/ioam6.c:861
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff8200aa60-ffffffff8200ab4a: ioam6_fill_trace_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ioam6_fill_trace_data(struct sk_buff *skb, struct ioam6_namespace *ns, struct ioam6_trace_hdr *trace, bool is_input);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6.c (ffffffff820d9a30)
Location: net/ipv6/ioam6.c:861
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
```
**Symbols:**

```
ffffffff820d9a30-ffffffff820d9b1a: ioam6_fill_trace_data (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_input</code>
</li>
</ul>
</details>
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
