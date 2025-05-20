# Function: <code>flow_rule_match_tcp</code>

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
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81931110)
Location: net/core/flow_offload.c:98
Inline: False
```
**Symbols:**

```
ffffffff81931110-ffffffff81931135: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963300)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81963300-ffffffff81963325: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a366c0)
Location: net/core/flow_offload.c:107
Inline: False
```
**Symbols:**

```
ffffffff81a366c0-ffffffff81a366e5: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a38a70)
Location: net/core/flow_offload.c:107
Inline: False
```
**Symbols:**

```
ffffffff81a38a70-ffffffff81a38a95: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a1fd20)
Location: net/core/flow_offload.c:107
Inline: False
```
**Symbols:**

```
ffffffff81a1fd20-ffffffff81a1fd45: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad3f60)
Location: net/core/flow_offload.c:107
Inline: False
```
**Symbols:**

```
ffffffff81ad3f60-ffffffff81ad3f85: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c523b0)
Location: net/core/flow_offload.c:128
Inline: False
```
**Symbols:**

```
ffffffff81c523b0-ffffffff81c523e1: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e07780)
Location: net/core/flow_offload.c:142
Inline: False
```
**Symbols:**

```
ffffffff81e07780-ffffffff81e077b1: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e7a0a0)
Location: net/core/flow_offload.c:142
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
```
**Symbols:**

```
ffffffff81e7a0a0-ffffffff81e7a0d1: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3a1f0)
Location: net/core/flow_offload.c:142
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
```
**Symbols:**

```
ffffffff81f3a1f0-ffffffff81f3a221: flow_rule_match_tcp (STB_GLOBAL)
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
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c075a0)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffff800010c075a0-ffff800010c075ec: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d205dc)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
c0d205dc-c0d20618: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf1c90)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
c000000000cf1c90-c000000000cf1cc0: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe0007857de)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffe0007857de-ffffffe00078581e: flow_rule_match_tcp (STB_GLOBAL)
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
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819032d0)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff819032d0-ffffffff819032f5: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd100)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff818bd100-ffffffff818bd125: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954300)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81954300-ffffffff81954325: flow_rule_match_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_rule_match_tcp(const struct flow_rule *rule, struct flow_match_tcp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81975fb0)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81975fb0-ffffffff81975fd5: flow_rule_match_tcp (STB_GLOBAL)
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
