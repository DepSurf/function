# Function: <code>ima_parse_buf</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff813fb010)
Location: security/integrity/ima/ima_template_lib.c:176
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff813fb010-ffffffff813fb0ff: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff814234b0)
Location: security/integrity/ima/ima_template_lib.c:176
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff814234b0-ffffffff8142359f: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffff81455af0)
Location: security/integrity/ima/ima_template_lib.c:178
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff81455af0-ffffffff81455be0: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:178
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff81473195-ffffffff814731b2: ima_parse_buf.cold.6 (STB_LOCAL)
ffffffff81472ed0-ffffffff81472fb4: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff814a0e75-ffffffff814a0eb2: ima_parse_buf.cold (STB_LOCAL)
ffffffff814a0b90-ffffffff814a0c60: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff814bb642-ffffffff814bb67f: ima_parse_buf.cold (STB_LOCAL)
ffffffff814bb230-ffffffff814bb300: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:179
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff8151baeb-ffffffff8151bb2a: ima_parse_buf.cold (STB_LOCAL)
ffffffff8151b670-ffffffff8151b735: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:179
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff81bf1f04-ffffffff81bf1f43: ima_parse_buf.cold (STB_LOCAL)
ffffffff81538520-ffffffff815385e5: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:179
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff81be3f28-ffffffff81be3f67: ima_parse_buf.cold (STB_LOCAL)
ffffffff81540c30-ffffffff81540cfd: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:219
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff81cd732f-ffffffff81cd73b0: ima_parse_buf.cold (STB_LOCAL)
ffffffff815a06f0-ffffffff815a07d0: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:241
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff81e8a55c-ffffffff81e8a5d3: ima_parse_buf.cold (STB_LOCAL)
ffffffff816464c0-ffffffff816465b7: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:241
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff820754a7-ffffffff820754ec: ima_parse_buf.cold (STB_LOCAL)
ffffffff816feb00-ffffffff816fec21: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:241
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff820f500f-ffffffff820f5054: ima_parse_buf.cold (STB_LOCAL)
ffffffff81738b70-ffffffff81738c9c: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:241
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_template_data
```
**Symbols:**

```
ffffffff821d219d-ffffffff821d21e2: ima_parse_buf.cold (STB_LOCAL)
ffffffff81779690-ffffffff817797bc: ima_parse_buf (STB_GLOBAL)
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
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffff8000105b3808)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffff8000105b3808-ffff8000105b3948: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (c0762c64)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
c0762c64-c0762d74: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (c000000000735fb0)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
c000000000735fb0-c000000000736140: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (ffffffe0003fad3c)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffe0003fad3c-ffffffe0003fae40: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff814b3c22-ffffffff814b3c5f: ima_parse_buf.cold (STB_LOCAL)
ffffffff814b3810-ffffffff814b38e0: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff814a4642-ffffffff814a467f: ima_parse_buf.cold (STB_LOCAL)
ffffffff814a4230-ffffffff814a4300: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff814afcb2-ffffffff814afcef: ima_parse_buf.cold (STB_LOCAL)
ffffffff814af8a0-ffffffff814af970: ima_parse_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_parse_buf(void *bufstartp, void *bufendp, void **bufcurp, int maxfields, struct ima_field_data *fields, int *curfields, long unsigned int *len_mask, int enforce_mask, char *bufname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template_lib.c (0)
Location: security/integrity/ima/ima_template_lib.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff814c8732-ffffffff814c876f: ima_parse_buf.cold (STB_LOCAL)
ffffffff814c8320-ffffffff814c83f0: ima_parse_buf (STB_GLOBAL)
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
