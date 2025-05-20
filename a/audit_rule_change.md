# Function: <code>audit_rule_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_rule_change(int type, __u32 portid, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81124750)
Location: kernel/auditfilter.c:1092
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81124750-ffffffff8112533d: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_rule_change(int type, __u32 portid, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112c850)
Location: kernel/auditfilter.c:1092
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8112c850-ffffffff8112d3de: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_rule_change(int type, __u32 portid, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81136560)
Location: kernel/auditfilter.c:1093
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81136560-ffffffff81137107: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137850)
Location: kernel/auditfilter.c:1092
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81137850-ffffffff811383f0: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81144550)
Location: kernel/auditfilter.c:1117
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81144550-ffffffff811450f4: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:1114
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8115442f-ffffffff8115447b: audit_rule_change.cold.19 (STB_LOCAL)
ffffffff81152ef0-ffffffff81153a76: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:1112
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8116124f-ffffffff8116129b: audit_rule_change.cold.19 (STB_LOCAL)
ffffffff8115fba0-ffffffff81160810: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (0)
Location: kernel/auditfilter.c:1116
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8116d941-ffffffff8116d95a: audit_rule_change.cold (STB_LOCAL)
ffffffff8116cab0-ffffffff8116ce89: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81178930)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81178930-ffffffff81178d27: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118bdc0)
Location: kernel/auditfilter.c:1124
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8118bdc0-ffffffff8118bf7b: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188fd0)
Location: kernel/auditfilter.c:1124
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81188fd0-ffffffff81189184: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81189d90)
Location: kernel/auditfilter.c:1124
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81189d90-ffffffff81189f41: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b27d0)
Location: kernel/auditfilter.c:1124
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811b27d0-ffffffff811b2981: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e4b20)
Location: kernel/auditfilter.c:1132
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811e4b20-ffffffff811e4cec: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8122ab30)
Location: kernel/auditfilter.c:1132
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8122ab30-ffffffff8122acfc: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81241110)
Location: kernel/auditfilter.c:1132
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81241110-ffffffff812412f4: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125af10)
Location: kernel/auditfilter.c:1133
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8125af10-ffffffff8125b0f7: audit_rule_change (STB_GLOBAL)
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
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101eda90)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffff8000101eda90-ffff8000101ede64: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042db60)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
c042db60-c042df88: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c000000000260430)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
c000000000260430-c000000000260910: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe000161f7a)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffe000161f7a-ffffffe0001622cc: audit_rule_change (STB_GLOBAL)
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
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81170f50)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81170f50-ffffffff81171347: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811640f0)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811640f0-ffffffff811644e7: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116ed20)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8116ed20-ffffffff8116f117: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_rule_change(int type, int seq, void *data, size_t datasz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8117c510)
Location: kernel/auditfilter.c:1123
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8117c510-ffffffff8117c907: audit_rule_change (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__u32 portid</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, portid, seq, data, datasz</code> ➡️ <code>type, seq, data, datasz</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
