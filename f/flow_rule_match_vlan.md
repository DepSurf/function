# Function: <code>flow_rule_match_vlan</code>

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
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81930ff0)
Location: net/core/flow_offload.c:56
Inline: False
```
**Symbols:**

```
ffffffff81930ff0-ffffffff81931015: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819631e0)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
ffffffff819631e0-ffffffff81963205: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a365a0)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff81a365a0-ffffffff81a365c5: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a38950)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff81a38950-ffffffff81a38975: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a1fc00)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff81a1fc00-ffffffff81a1fc25: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad3e40)
Location: net/core/flow_offload.c:65
Inline: False
```
**Symbols:**

```
ffffffff81ad3e40-ffffffff81ad3e65: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c52230)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffff81c52230-ffffffff81c52261: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e07500)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffff81e07500-ffffffff81e07531: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e79e20)
Location: net/core/flow_offload.c:86
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_vlan_usage
```
**Symbols:**

```
ffffffff81e79e20-ffffffff81e79e51: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f39f70)
Location: net/core/flow_offload.c:86
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_vlan_usage
```
**Symbols:**

```
ffffffff81f39f70-ffffffff81f39fa1: flow_rule_match_vlan (STB_GLOBAL)
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
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c073c0)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
ffff800010c073c0-ffff800010c0740c: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d20474)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
c0d20474-c0d204b0: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf1b70)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
c000000000cf1b70-c000000000cf1ba0: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe00078565e)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
ffffffe00078565e-ffffffe00078569e: flow_rule_match_vlan (STB_GLOBAL)
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
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819031b0)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
ffffffff819031b0-ffffffff819031d5: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bcfe0)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
ffffffff818bcfe0-ffffffff818bd005: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819541e0)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
ffffffff819541e0-ffffffff81954205: flow_rule_match_vlan (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_rule_match_vlan(const struct flow_rule *rule, struct flow_match_vlan *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81975e90)
Location: net/core/flow_offload.c:58
Inline: False
```
**Symbols:**

```
ffffffff81975e90-ffffffff81975eb5: flow_rule_match_vlan (STB_GLOBAL)
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
