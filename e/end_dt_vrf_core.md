# Function: <code>end_dt_vrf_core</code>

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
struct sk_buff *end_dt_vrf_core(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8eb00)
Location: net/ipv6/seg6_local.c:595
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
```
**Symbols:**

```
ffffffff81b8eb00-ffffffff81b8ec31: end_dt_vrf_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *end_dt_vrf_core(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7dbf0)
Location: net/ipv6/seg6_local.c:624
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
```
**Symbols:**

```
ffffffff81b7dbf0-ffffffff81b7dd21: end_dt_vrf_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *end_dt_vrf_core(struct sk_buff *skb, struct seg6_local_lwt *slwt, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:614
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
```
**Symbols:**

```
ffffffff81c48ef0-ffffffff81c490b6: end_dt_vrf_core (STB_LOCAL)
ffffffff81d41638-ffffffff81d41664: end_dt_vrf_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *end_dt_vrf_core(struct sk_buff *skb, struct seg6_local_lwt *slwt, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:616
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
```
**Symbols:**

```
ffffffff81de85e0-ffffffff81de87df: end_dt_vrf_core (STB_LOCAL)
ffffffff81f0dfac-ffffffff81f0dfd9: end_dt_vrf_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *end_dt_vrf_core(struct sk_buff *skb, struct seg6_local_lwt *slwt, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:741
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
```
**Symbols:**

```
ffffffff81fbb720-ffffffff81fbb92e: end_dt_vrf_core (STB_LOCAL)
ffffffff820b5354-ffffffff820b5369: end_dt_vrf_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *end_dt_vrf_core(struct sk_buff *skb, struct seg6_local_lwt *slwt, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:1068
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
```
**Symbols:**

```
ffffffff8201bde0-ffffffff8201bfd8: end_dt_vrf_core (STB_LOCAL)
ffffffff821361e5-ffffffff821361fa: end_dt_vrf_core.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *end_dt_vrf_core(struct sk_buff *skb, struct seg6_local_lwt *slwt, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (0)
Location: net/ipv6/seg6_local.c:1128
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
```
**Symbols:**

```
ffffffff820eadb0-ffffffff820eafa4: end_dt_vrf_core (STB_LOCAL)
ffffffff82217db5-ffffffff82217dca: end_dt_vrf_core.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 family</code>
</li>
</ul>
</details>
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
