# Function: <code>flow_rule_match_cvlan</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81931020)
Location: net/core/flow_offload.c:63
Inline: False
```
**Symbols:**

```
ffffffff81931020-ffffffff81931045: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963210)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff81963210-ffffffff81963235: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a365d0)
Location: net/core/flow_offload.c:72
Inline: False
```
**Symbols:**

```
ffffffff81a365d0-ffffffff81a365f5: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a38980)
Location: net/core/flow_offload.c:72
Inline: False
```
**Symbols:**

```
ffffffff81a38980-ffffffff81a389a5: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a1fc30)
Location: net/core/flow_offload.c:72
Inline: False
```
**Symbols:**

```
ffffffff81a1fc30-ffffffff81a1fc55: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad3e70)
Location: net/core/flow_offload.c:72
Inline: False
```
**Symbols:**

```
ffffffff81ad3e70-ffffffff81ad3e95: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c52270)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff81c52270-ffffffff81c522a1: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e07550)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff81e07550-ffffffff81e07581: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e79e70)
Location: net/core/flow_offload.c:93
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_cvlan_usage
```
**Symbols:**

```
ffffffff81e79e70-ffffffff81e79ea1: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f39fc0)
Location: net/core/flow_offload.c:93
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_cvlan_usage
```
**Symbols:**

```
ffffffff81f39fc0-ffffffff81f39ff1: flow_rule_match_cvlan (STB_GLOBAL)
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
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c07410)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffff800010c07410-ffff800010c0745c: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d204b0)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
c0d204b0-c0d204ec: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf1ba0)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
c000000000cf1ba0-c000000000cf1bd0: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe00078569e)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffe00078569e-ffffffe0007856de: flow_rule_match_cvlan (STB_GLOBAL)
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
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819031e0)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff819031e0-ffffffff81903205: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd010)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff818bd010-ffffffff818bd035: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954210)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff81954210-ffffffff81954235: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_rule_match_cvlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81975ec0)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff81975ec0-ffffffff81975ee5: flow_rule_match_cvlan (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
