# Function: <code>ima_filter_rule_match</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_filter_rule_match(struct lsmblob *blob, u32 field, u32 op, void *lsmrule, int lsmslot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815be790)
Location: security/security.c:3101
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
**Symbols:**

```
ffffffff815be790-ffffffff815be805: ima_filter_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_filter_rule_match(struct lsmblob *blob, u32 field, u32 op, void *lsmrule, int lsmslot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166aa00)
Location: security/security.c:3081
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
**Symbols:**

```
ffffffff8166aa00-ffffffff8166aa75: ima_filter_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_filter_rule_match(struct lsmblob *blob, u32 field, u32 op, void *lsmrule, int lsmslot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a3130)
Location: security/security.c:5470
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
**Symbols:**

```
ffffffff816a3130-ffffffff816a31d3: ima_filter_rule_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_filter_rule_match(struct lsmblob *blob, u32 field, u32 op, void *lsmrule, int lsmid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dfbc0)
Location: security/security.c:5617
Inline: False
```
**Symbols:**

```
ffffffff816dfbc0-ffffffff816dfc57: ima_filter_rule_match (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int lsmid</code>
</li>
<li>
<b>Param removed. </b>
<code>int lsmslot</code>
</li>
</ul>
</details>
</li>
</ul>
