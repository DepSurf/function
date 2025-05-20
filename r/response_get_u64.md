# Function: <code>response_get_u64</code>

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
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145b0c0)
Location: block/sed-opal.c:883
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff8145b0c0-ffffffff8145b179: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81486e90)
Location: block/sed-opal.c:895
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff81486e90-ffffffff81486f49: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bbde0)
Location: block/sed-opal.c:912
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff814bbde0-ffffffff814bbe9d: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d01a0)
Location: block/sed-opal.c:912
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff814d01a0-ffffffff814d025d: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814fe9b0)
Location: block/sed-opal.c:951
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff814fe9b0-ffffffff814fea23: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151c900)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff8151c900-ffffffff8151c973: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157c760)
Location: block/sed-opal.c:952
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:response_status
```
**Symbols:**

```
ffffffff8157c760-ffffffff8157c7d3: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815997a0)
Location: block/sed-opal.c:952
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:response_status
```
**Symbols:**

```
ffffffff815997a0-ffffffff81599813: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a04f0)
Location: block/sed-opal.c:952
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff815a04f0-ffffffff815a0563: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81608d10)
Location: block/sed-opal.c:952
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff81608d10-ffffffff81608d7d: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bcaf0)
Location: block/sed-opal.c:952
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff816bcaf0-ffffffff816bcb6b: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177d560)
Location: block/sed-opal.c:992
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff8177d560-ffffffff8177d5dd: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bd000)
Location: block/sed-opal.c:1000
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff817bd000-ffffffff817bd07d: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff818016c0)
Location: block/sed-opal.c:1117
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:response_get_column
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff818016c0-ffffffff8180173d: response_get_u64 (STB_LOCAL)
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
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625418)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffff800010625418-ffff8000106254e8: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cce78)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
c07cce78-c07ccf2c: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c6120)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
c0000000007c6120-c0000000007c6214: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000456656)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffe000456656-ffffffe00045670c: response_get_u64 (STB_LOCAL)
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
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81514ee0)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff81514ee0-ffffffff81514f53: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815051f0)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff815051f0-ffffffff81505263: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81510f70)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff81510f70-ffffffff81510fe3: response_get_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 response_get_u64(const struct parsed_resp *resp, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152a730)
Location: block/sed-opal.c:950
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff8152a730-ffffffff8152a7a3: response_get_u64 (STB_LOCAL)
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
