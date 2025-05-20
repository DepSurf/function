# Function: <code>seg6_get_srh</code>

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
struct ipv6_sr_hdr *seg6_get_srh(struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81c380d0)
Location: net/ipv6/seg6.c:78
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81c380d0-ffffffff81c381d3: seg6_get_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ipv6_sr_hdr *seg6_get_srh(struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81dd5cf0)
Location: net/ipv6/seg6.c:78
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81dd5cf0-ffffffff81dd5e06: seg6_get_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ipv6_sr_hdr *seg6_get_srh(struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff81fa74f0)
Location: net/ipv6/seg6.c:78
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81fa74f0-ffffffff81fa7606: seg6_get_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ipv6_sr_hdr *seg6_get_srh(struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff82007d50)
Location: net/ipv6/seg6.c:78
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff82007d50-ffffffff82007e66: seg6_get_srh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ipv6_sr_hdr *seg6_get_srh(struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (ffffffff820d6c70)
Location: net/ipv6/seg6.c:78
Inline: False
Direct callers:
  - net/ipv6/seg6.c:seg6_icmp_srh
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:input_action_end_x_core
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff820d6c70-ffffffff820d6d86: seg6_get_srh (STB_GLOBAL)
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
