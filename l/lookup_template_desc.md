# Function: <code>lookup_template_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81399c40)
Location: security/integrity/ima/ima_template.c:102
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81399c40-ffffffff81399c95: lookup_template_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813d6a90)
Location: security/integrity/ima/ima_template.c:100
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff813d6a90-ffffffff813d6af0: lookup_template_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813ede30)
Location: security/integrity/ima/ima_template.c:108
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
```
**Symbols:**

```
ffffffff813ede30-ffffffff813ede8f: lookup_template_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813fa290)
Location: security/integrity/ima/ima_template.c:111
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff813fa290-ffffffff813fa2ef: lookup_template_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81422730)
Location: security/integrity/ima/ima_template.c:111
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff81422730-ffffffff8142278f: lookup_template_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81454e60)
Location: security/integrity/ima/ima_template.c:111
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff81454e60-ffffffff81454ebf: lookup_template_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81472240)
Location: security/integrity/ima/ima_template.c:111
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff81472240-ffffffff8147229f: lookup_template_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814a0120)
Location: security/integrity/ima/ima_template.c:112
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff814a0120-ffffffff814a0183: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814ba780)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff814ba780-ffffffff814ba7e3: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8151ad40)
Location: security/integrity/ima/ima_template.c:134
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff8151ad40-ffffffff8151adb1: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81537c90)
Location: security/integrity/ima/ima_template.c:135
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_buf
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff81537c90-ffffffff81537d0b: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff815402e0)
Location: security/integrity/ima/ima_template.c:135
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_buf
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff815402e0-ffffffff81540358: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8159fb00)
Location: security/integrity/ima/ima_template.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_buf
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff8159fb00-ffffffff8159fb78: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81645220)
Location: security/integrity/ima/ima_template.c:163
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_buf
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff81645220-ffffffff8164529e: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff816fd6a0)
Location: security/integrity/ima/ima_template.c:163
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff816fd6a0-ffffffff816fd71e: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff817376c0)
Location: security/integrity/ima/ima_template.c:163
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff817376c0-ffffffff8173773e: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff817781b0)
Location: security/integrity/ima/ima_template.c:163
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff817781b0-ffffffff8177822e: lookup_template_desc (STB_GLOBAL)
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
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffff8000105b2ba8)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffff8000105b2ba8-ffff8000105b2c38: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (c07621f8)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
c07621f8-c0762270: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (c000000000734e90)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
c000000000734e90-c0000000007351f0: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffe0003fa198)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffe0003fa198-ffffffe0003fa208: lookup_template_desc (STB_GLOBAL)
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
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814b2d60)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff814b2d60-ffffffff814b2dc3: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814a3780)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff814a3780-ffffffff814a37e3: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814aedf0)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff814aedf0-ffffffff814aee53: lookup_template_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ima_template_desc *lookup_template_desc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814c7860)
Location: security/integrity/ima/ima_template.c:136
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_desc_current
  - security/integrity/ima/ima_template.c:ima_template_setup
```
**Symbols:**

```
ffffffff814c7860-ffffffff814c78d2: lookup_template_desc (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
