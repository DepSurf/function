# Function: <code>get_srh</code>

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
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8194f440)
Location: net/ipv6/seg6_local.c:62
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff8194f440-ffffffff8194f533: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819a86e0)
Location: net/ipv6/seg6_local.c:71
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff819a86e0-ffffffff819a87d4: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819df230)
Location: net/ipv6/seg6_local.c:71
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff819df230-ffffffff819df318: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a4dda0)
Location: net/ipv6/seg6_local.c:66
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a4dda0-ffffffff81a4de92: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a84970)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a84970-ffffffff81a84a65: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7fa50)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81b7fa50-ffffffff81b7fb4a: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8ed80)
Location: net/ipv6/seg6_local.c:120
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81b8ed80-ffffffff81b8ee7a: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7ddb0)
Location: net/ipv6/seg6_local.c:152
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:decap_and_validate
```
**Symbols:**

```
ffffffff81b7ddb0-ffffffff81b7dead: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffff800010d509d8)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffff800010d509d8-ffff800010d50b00: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c0e51520)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
c0e51520-c0e51654: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c000000000e88720)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
c000000000e88720-c000000000e888bc: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffe000888dcc)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffe000888dcc-ffffffe000888ea8: get_srh (STB_LOCAL)
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
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a24000)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a24000-ffffffff81a240f5: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819e0dc0)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff819e0dc0-ffffffff819e0eb5: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a8ea80)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a8ea80-ffffffff81a8eb75: get_srh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ipv6_sr_hdr *get_srh(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a9b7f0)
Location: net/ipv6/seg6_local.c:67
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:decap_and_validate
  - net/ipv6/seg6_local.c:get_and_validate_srh
```
**Symbols:**

```
ffffffff81a9b7f0-ffffffff81a9b8e5: get_srh (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
