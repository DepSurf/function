# Function: <code>template_desc_init_fields</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int template_desc_init_fields(const char *template_fmt, struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8139beec)
Location: security/integrity/ima/ima_template.c:141
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff8139beec-ffffffff8139c0e0: template_desc_init_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int template_desc_init_fields(const char *template_fmt, struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813d8dd6)
Location: security/integrity/ima/ima_template.c:139
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff813d8dd6-ffffffff813d8fca: template_desc_init_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813ee376)
Location: security/integrity/ima/ima_template.c:152
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff813edf00-ffffffff813ee1c0: template_desc_init_fields.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813fa8bc)
Location: security/integrity/ima/ima_template.c:155
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff813fa3b0-ffffffff813fa67e: template_desc_init_fields.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81422d5c)
Location: security/integrity/ima/ima_template.c:155
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81422850-ffffffff81422b1e: template_desc_init_fields.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8145533b)
Location: security/integrity/ima/ima_template.c:155
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff81454ec0-ffffffff814550d0: template_desc_init_fields.part.1 (STB_LOCAL)
ffffffff81455603-ffffffff81455628: template_desc_init_fields.part.1.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8147271b)
Location: security/integrity/ima/ima_template.c:156
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff814722a0-ffffffff814724b0: template_desc_init_fields.part.1 (STB_LOCAL)
ffffffff814729e3-ffffffff81472a08: template_desc_init_fields.part.1.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814a03e9)
Location: security/integrity/ima/ima_template.c:157
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff8149ff20-ffffffff814a0118: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff814a06ba-ffffffff814a06f5: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff814a0190-ffffffff814a01ae: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814baa4c)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff814ba520-ffffffff814ba718: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff814bad54-ffffffff814bad8f: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff814ba7f0-ffffffff814ba80e: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8151af5d)
Location: security/integrity/ima/ima_template.c:179
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:restore_template_fmt
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:restore_template_fmt
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff8151a800-ffffffff8151aa03: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff8151b186-ffffffff8151b1c1: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff8151adc0-ffffffff8151adde: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81537efd)
Location: security/integrity/ima/ima_template.c:180
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:restore_template_fmt
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:restore_template_fmt
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff81537770-ffffffff8153796c: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff81bf1e3b-ffffffff81bf1e76: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff81537d10-ffffffff81537d2e: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81540573)
Location: security/integrity/ima/ima_template.c:180
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff8153fe60-ffffffff8154005d: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff81be3e62-ffffffff81be3e9d: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff81540360-ffffffff8154037e: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8159fdc0)
Location: security/integrity/ima/ima_template.c:204
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff8159f580-ffffffff8159f847: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff81cd71a6-ffffffff81cd720e: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff8159fb80-ffffffff8159fb9e: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (0)
Location: security/integrity/ima/ima_template.c:208
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff81e8a41d-ffffffff81e8a458: template_desc_init_fields.cold (STB_LOCAL)
ffffffff816452a0-ffffffff816455da: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff816fd730)
Location: security/integrity/ima/ima_template.c:208
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff816fd730-ffffffff816fdaa5: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81737750)
Location: security/integrity/ima/ima_template.c:208
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff81737750-ffffffff81737ac5: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81778240)
Location: security/integrity/ima/ima_template.c:208
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff81778240-ffffffff817785b5: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffff8000105b30b8)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffff8000105b28d8-ffff8000105b2af8: template_desc_init_fields.part.0 (STB_LOCAL)
ffff8000105b2c38-ffff8000105b2c90: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (c07626e0)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
c0761f5c-c076216c: template_desc_init_fields.part.0 (STB_LOCAL)
c0762270-c07622a8: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (c000000000735750)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
c000000000734a90-c000000000734dac: template_desc_init_fields.part.0 (STB_LOCAL)
c0000000007351f0-c000000000735228: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffe0003fa208)
Location: security/integrity/ima/ima_template.c:181
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffe0003fa208-ffffffe0003fa3ac: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814b302c)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff814b2b00-ffffffff814b2cf8: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff814b3334-ffffffff814b336f: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff814b2dd0-ffffffff814b2dee: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814a3a4c)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff814a3520-ffffffff814a3718: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff814a3d54-ffffffff814a3d8f: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff814a37f0-ffffffff814a380e: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814af0bc)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff814aeb90-ffffffff814aed88: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff814af3c4-ffffffff814af3ff: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff814aee60-ffffffff814aee7e: template_desc_init_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int template_desc_init_fields(const char *template_fmt, const struct ima_template_field ***fields, int *num_fields);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff814c7b3c)
Location: security/integrity/ima/ima_template.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_init_template
  - security/integrity/ima/ima_template.c:ima_template_fmt_setup
```
**Symbols:**

```
ffffffff814c7600-ffffffff814c77f8: template_desc_init_fields.part.0 (STB_LOCAL)
ffffffff814c7e42-ffffffff814c7e7d: template_desc_init_fields.part.0.cold (STB_LOCAL)
ffffffff814c78e0-ffffffff814c78fe: template_desc_init_fields (STB_GLOBAL)
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
