# Function: <code>flow_rule_match_ports</code>

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
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819310e0)
Location: net/core/flow_offload.c:91
Inline: False
```
**Symbols:**

```
ffffffff819310e0-ffffffff81931105: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819632d0)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff819632d0-ffffffff819632f5: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a36690)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81a36690-ffffffff81a366b5: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a38a40)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81a38a40-ffffffff81a38a65: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a1fcf0)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81a1fcf0-ffffffff81a1fd15: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad3f30)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81ad3f30-ffffffff81ad3f55: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c52370)
Location: net/core/flow_offload.c:121
Inline: False
```
**Symbols:**

```
ffffffff81c52370-ffffffff81c523a1: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e076e0)
Location: net/core/flow_offload.c:128
Inline: False
```
**Symbols:**

```
ffffffff81e076e0-ffffffff81e07711: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e7a000)
Location: net/core/flow_offload.c:128
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_portnum_usage
```
**Symbols:**

```
ffffffff81e7a000-ffffffff81e7a031: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3a150)
Location: net/core/flow_offload.c:128
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_portnum_usage
```
**Symbols:**

```
ffffffff81f3a150-ffffffff81f3a181: flow_rule_match_ports (STB_GLOBAL)
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
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c07550)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffff800010c07550-ffff800010c0759c: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d205a0)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
c0d205a0-c0d205dc: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf1c60)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
c000000000cf1c60-c000000000cf1c90: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe00078579e)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffe00078579e-ffffffe0007857de: flow_rule_match_ports (STB_GLOBAL)
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
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819032a0)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff819032a0-ffffffff819032c5: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd0d0)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff818bd0d0-ffffffff818bd0f5: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819542d0)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff819542d0-ffffffff819542f5: flow_rule_match_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_rule_match_ports(const struct flow_rule *rule, struct flow_match_ports *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81975f80)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff81975f80-ffffffff81975fa5: flow_rule_match_ports (STB_GLOBAL)
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
