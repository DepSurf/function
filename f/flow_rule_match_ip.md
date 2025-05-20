# Function: <code>flow_rule_match_ip</code>

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
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819310b0)
Location: net/core/flow_offload.c:84
Inline: False
```
**Symbols:**

```
ffffffff819310b0-ffffffff819310d5: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819632a0)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffff819632a0-ffffffff819632c5: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a36660)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff81a36660-ffffffff81a36685: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a38a10)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff81a38a10-ffffffff81a38a35: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a1fcc0)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff81a1fcc0-ffffffff81a1fce5: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad3f00)
Location: net/core/flow_offload.c:93
Inline: False
```
**Symbols:**

```
ffffffff81ad3f00-ffffffff81ad3f25: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c52330)
Location: net/core/flow_offload.c:114
Inline: False
```
**Symbols:**

```
ffffffff81c52330-ffffffff81c52361: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e07690)
Location: net/core/flow_offload.c:121
Inline: False
```
**Symbols:**

```
ffffffff81e07690-ffffffff81e076c1: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e79fb0)
Location: net/core/flow_offload.c:121
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ip_usage
```
**Symbols:**

```
ffffffff81e79fb0-ffffffff81e79fe1: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3a100)
Location: net/core/flow_offload.c:121
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ip_usage
```
**Symbols:**

```
ffffffff81f3a100-ffffffff81f3a131: flow_rule_match_ip (STB_GLOBAL)
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
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c07500)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffff800010c07500-ffff800010c0754c: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d20564)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
c0d20564-c0d205a0: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf1c30)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
c000000000cf1c30-c000000000cf1c60: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe00078575e)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffe00078575e-ffffffe00078579e: flow_rule_match_ip (STB_GLOBAL)
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
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81903270)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffff81903270-ffffffff81903295: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd0a0)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffff818bd0a0-ffffffff818bd0c5: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819542a0)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffff819542a0-ffffffff819542c5: flow_rule_match_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_rule_match_ip(const struct flow_rule *rule, struct flow_match_ip *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81975f50)
Location: net/core/flow_offload.c:86
Inline: False
```
**Symbols:**

```
ffffffff81975f50-ffffffff81975f75: flow_rule_match_ip (STB_GLOBAL)
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
