# Function: <code>widen_string</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff814398f0)
Location: lib/vsprintf.c:562
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff814398f0-ffffffff8143998f: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff814568d0)
Location: lib/vsprintf.c:562
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff814568d0-ffffffff8145696f: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f8120)
Location: lib/vsprintf.c:563
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff818f8120-ffffffff818f81bc: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197ebe0)
Location: lib/vsprintf.c:565
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff8197ebe0-ffffffff8197ec7c: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819db170)
Location: lib/vsprintf.c:574
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff819db170-ffffffff819db205: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a13450)
Location: lib/vsprintf.c:575
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81a13450-ffffffff81a134e5: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a828c0)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffffffff81a828c0-ffffffff81a8295b: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ab9ad0)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffffffff81ab9ad0-ffffffff81ab9b6b: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f4700)
Location: lib/vsprintf.c:580
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff815f4700-ffffffff815f4793: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81618d70)
Location: lib/vsprintf.c:583
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81618d70-ffffffff81618e03: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fc3f0)
Location: lib/vsprintf.c:609
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff815fc3f0-ffffffff815fc483: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81669a30)
Location: lib/vsprintf.c:610
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81669a30-ffffffff81669ac3: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81783640)
Location: lib/vsprintf.c:615
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81783640-ffffffff817836c4: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82041180)
Location: lib/vsprintf.c:616
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff82041180-ffffffff82041204: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820bf690)
Location: lib/vsprintf.c:616
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff820bf690-ffffffff820bf714: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219a940)
Location: lib/vsprintf.c:618
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff8219a940-ffffffff8219a9c4: widen_string (STB_LOCAL)
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
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d94220)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffff800010d94220-ffff800010d942f4: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e9054c)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
c0e9054c-c0e90610: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed8ac0)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
c000000000ed8ac0-c000000000ed8bdc: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008be166)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffffffe0008be166-ffffffe0008be226: widen_string (STB_LOCAL)
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
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a58920)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffffffff81a58920-ffffffff81a589bb: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15a00)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffffffff81a15a00-ffffffff81a15a9b: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac4d10)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffffffff81ac4d10-ffffffff81ac4dab: widen_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *widen_string(char *buf, int n, char *end, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad11e0)
Location: lib/vsprintf.c:577
Inline: False
Direct callers:
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string_nocheck
```
**Symbols:**

```
ffffffff81ad11e0-ffffffff81ad127b: widen_string (STB_LOCAL)
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
