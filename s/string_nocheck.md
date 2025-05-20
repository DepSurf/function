# Function: <code>string_nocheck</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a82960)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffffffff81a82960-ffffffff81a829b5: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ab9b70)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffffffff81ab9b70-ffffffff81ab9bc5: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f84ee)
Location: lib/vsprintf.c:601
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161cbae)
Location: lib/vsprintf.c:604
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff816004bf)
Location: lib/vsprintf.c:630
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
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
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166e41c)
Location: lib/vsprintf.c:631
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
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
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff817886d0)
Location: lib/vsprintf.c:636
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
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
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82045a1e)
Location: lib/vsprintf.c:637
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
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
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c407e)
Location: lib/vsprintf.c:637
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
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
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219e9fe)
Location: lib/vsprintf.c:639
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
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
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:symbol_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:string
  - lib/vsprintf.c:string
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
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d942f8)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffff800010d942f8-ffff800010d94364: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e90610)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:ip4_addr_string_sa
  - lib/vsprintf.c:ip6_addr_string_sa
  - lib/vsprintf.c:ip4_addr_string
  - lib/vsprintf.c:ip6_addr_string
  - lib/vsprintf.c:mac_address_string
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
c0e90610-c0e9068c: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed8be0)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
c000000000ed8be0-c000000000ed8c48: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008be226)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:device_node_gen_full_name
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffffffe0008be226-ffffffe0008be278: string_nocheck (STB_LOCAL)
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
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a589c0)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffffffff81a589c0-ffffffff81a58a15: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15aa0)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffffffff81a15aa0-ffffffff81a15af5: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac4db0)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffffffff81ac4db0-ffffffff81ac4e05: string_nocheck (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *string_nocheck(char *buf, char *end, const char *s, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad1280)
Location: lib/vsprintf.c:598
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:time_and_date
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
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:string
  - lib/vsprintf.c:check_pointer
```
**Symbols:**

```
ffffffff81ad1280-ffffffff81ad12d5: string_nocheck (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
