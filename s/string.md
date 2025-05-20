# Function: <code>string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff813f3860)
Location: lib/vsprintf.c:511
Inline: False
Direct callers:
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:bstr_printf
```
**Symbols:**

```
ffffffff813f3860-ffffffff813f3925: string.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81439990)
Location: lib/vsprintf.c:583
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81439990-ffffffff81439a02: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81456970)
Location: lib/vsprintf.c:583
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff81456970-ffffffff814569e2: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f81c0)
Location: lib/vsprintf.c:584
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff818f81c0-ffffffff818f8246: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197ec80)
Location: lib/vsprintf.c:586
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:clock
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff8197ec80-ffffffff8197ed06: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819db210)
Location: lib/vsprintf.c:595
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:symbol_string
```
**Symbols:**

```
ffffffff819db210-ffffffff819db28a: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a134f0)
Location: lib/vsprintf.c:596
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:ptr_to_id
```
**Symbols:**

```
ffffffff81a134f0-ffffffff81a1356a: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a82b70)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81a82b70-ffffffff81a82bc6: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ab9d80)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81ab9d80-ffffffff81ab9dd6: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f5950)
Location: lib/vsprintf.c:684
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff815f5950-ffffffff815f5a20: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81619fd0)
Location: lib/vsprintf.c:687
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81619fd0-ffffffff8161a0a0: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fe0b0)
Location: lib/vsprintf.c:713
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:format_flags
  - lib/vsprintf.c:fourcc_string
```
**Symbols:**

```
ffffffff815fe0b0-ffffffff815fe180: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166bd80)
Location: lib/vsprintf.c:714
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:format_flags
  - lib/vsprintf.c:fourcc_string
```
**Symbols:**

```
ffffffff8166bd80-ffffffff8166be50: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81785db0)
Location: lib/vsprintf.c:719
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:format_flags
  - lib/vsprintf.c:fourcc_string
```
**Symbols:**

```
ffffffff81785db0-ffffffff81785eb4: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82042e40)
Location: lib/vsprintf.c:720
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:format_flags
  - lib/vsprintf.c:fourcc_string
```
**Symbols:**

```
ffffffff82042e40-ffffffff82042f44: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c13e0)
Location: lib/vsprintf.c:720
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:format_flags
  - lib/vsprintf.c:fourcc_string
```
**Symbols:**

```
ffffffff820c13e0-ffffffff820c14e4: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219bd10)
Location: lib/vsprintf.c:722
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:fwnode_full_name_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:format_flags
  - lib/vsprintf.c:fourcc_string
```
**Symbols:**

```
ffffffff8219bd10-ffffffff8219be14: string (STB_LOCAL)
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
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d94528)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffff800010d94528-ffff800010d9458c: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e90838)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
c0e90838-c0e9089c: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed8ec0)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
c000000000ed8ec0-c000000000ed8f30: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008be404)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffe0008be404-ffffffe0008be45a: string (STB_LOCAL)
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
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a58bd0)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81a58bd0-ffffffff81a58c26: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15cb0)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81a15cb0-ffffffff81a15d06: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac4fc0)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81ac4fc0-ffffffff81ac5016: string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *string(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad1490)
Location: lib/vsprintf.c:662
Inline: False
Direct callers:
  - lib/vsprintf.c:bstr_printf
  - lib/vsprintf.c:vsnprintf
  - lib/vsprintf.c:flags_string
```
**Symbols:**

```
ffffffff81ad1490-ffffffff81ad14e6: string (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
