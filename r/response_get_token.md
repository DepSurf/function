# Function: <code>response_get_token</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145b040)
Location: block/sed-opal.c:675
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff8145b040-ffffffff8145b0b9: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81486e10)
Location: block/sed-opal.c:687
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff81486e10-ffffffff81486e89: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bbd60)
Location: block/sed-opal.c:684
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff814bbd60-ffffffff814bbddb: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d0120)
Location: block/sed-opal.c:684
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff814d0120-ffffffff814d019b: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814fe910)
Location: block/sed-opal.c:726
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffffffff814fe910-ffffffff814fe9ac: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151c860)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffffffff8151c860-ffffffff8151c8fc: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157c6c0)
Location: block/sed-opal.c:730
Inline: False
Direct callers:
  - block/sed-opal.c:response_status
  - block/sed-opal.c:response_status
  - block/sed-opal.c:response_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff8157c6c0-ffffffff8157c75c: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81599700)
Location: block/sed-opal.c:730
Inline: False
Direct callers:
  - block/sed-opal.c:response_status
  - block/sed-opal.c:response_status
  - block/sed-opal.c:response_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff81599700-ffffffff8159979c: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a0450)
Location: block/sed-opal.c:730
Inline: False
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff815a0450-ffffffff815a04ec: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81608c70)
Location: block/sed-opal.c:730
Inline: False
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff81608c70-ffffffff81608d03: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bca50)
Location: block/sed-opal.c:730
Inline: False
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff816bca50-ffffffff816bcae6: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177d4b0)
Location: block/sed-opal.c:770
Inline: False
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff8177d4b0-ffffffff8177d546: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bcf20)
Location: block/sed-opal.c:778
Inline: False
Direct callers:
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff817bcf20-ffffffff817bcfe9: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff818015e0)
Location: block/sed-opal.c:891
Inline: False
Direct callers:
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
  - block/sed-opal.c:response_get_string
```
**Symbols:**

```
ffffffff818015e0-ffffffff818016a9: response_get_token (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625328)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffff800010625328-ffff800010625414: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07ccd90)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
c07ccd90-c07cce78: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c6000)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
c0000000007c6000-c0000000007c6120: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000456592)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffffffe000456592-ffffffe000456656: response_get_token (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81514e40)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffffffff81514e40-ffffffff81514edc: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81505150)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffffffff81505150-ffffffff815051ec: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81510ed0)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffffffff81510ed0-ffffffff81510f6c: response_get_token (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct opal_resp_tok *response_get_token(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152a690)
Location: block/sed-opal.c:728
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:parse_and_check_status
  - block/sed-opal.c:response_get_u64
```
**Symbols:**

```
ffffffff8152a690-ffffffff8152a72c: response_get_token (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
