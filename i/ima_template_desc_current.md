# Function: <code>ima_template_desc_current</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81399ca0)
Location: security/integrity/ima/ima_template.c:187
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
**Symbols:**

```
ffffffff81399ca0-ffffffff81399ccb: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81fc5194)
Location: security/integrity/ima/ima_template.c:185
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
```
**Symbols:**

```
ffffffff813d6af0-ffffffff813d6b1b: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813ee1e0)
Location: security/integrity/ima/ima_template.c:218
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff813ee1e0-ffffffff813ee221: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813fa6b0)
Location: security/integrity/ima/ima_template.c:221
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff813fa6b0-ffffffff813fa6f2: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81422b50)
Location: security/integrity/ima/ima_template.c:221
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81422b50-ffffffff81422b92: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81455140)
Location: security/integrity/ima/ima_template.c:221
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81455140-ffffffff81455170: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81472520)
Location: security/integrity/ima/ima_template.c:222
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81472520-ffffffff81472550: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814a0220)
Location: security/integrity/ima/ima_template.c:223
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff814a0220-ffffffff814a0250: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814ba880)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff814ba880-ffffffff814ba8b0: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8151ae00)
Location: security/integrity/ima/ima_template.c:245
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff8151ae00-ffffffff8151ae41: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81537d50)
Location: security/integrity/ima/ima_template.c:246
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81537d50-ffffffff81537d91: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff815403a0)
Location: security/integrity/ima/ima_template.c:246
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff815403a0-ffffffff815403e1: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8159fbc0)
Location: security/integrity/ima/ima_template.c:270
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff8159fbc0-ffffffff8159fc01: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81645690)
Location: security/integrity/ima/ima_template.c:274
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81645690-ffffffff81645755: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff83ed7015)
Location: security/integrity/ima/ima_template.c:274
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff816fdb80-ffffffff816fdc45: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff836fc1c5)
Location: security/integrity/ima/ima_template.c:274
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81737ba0-ffffffff81737c65: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8392f7b5)
Location: security/integrity/ima/ima_template.c:274
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
**Symbols:**

```
ffffffff81778690-ffffffff81778755: ima_template_desc_current (STB_GLOBAL)
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
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffff8000105b2d70)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffff8000105b2d70-ffff8000105b2dbc: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (c0762334)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
c0762334-c0762374: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (c000000000735330)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
c000000000735330-c000000000735384: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffe0003fa460)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffe0003fa460-ffffffe0003fa4ae: ima_template_desc_current (STB_GLOBAL)
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
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814b2e60)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff814b2e60-ffffffff814b2e90: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814a3880)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff814a3880-ffffffff814a38b0: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814aeef0)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff814aeef0-ffffffff814aef20: ima_template_desc_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814c7970)
Location: security/integrity/ima/ima_template.c:247
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:hash_setup
  - security/integrity/ima/ima_api.c:ima_alloc_init_template
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff814c7970-ffffffff814c79a0: ima_template_desc_current (STB_GLOBAL)
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
