# Function: <code>check_pointer</code>

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
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a829c0)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81a829c0-ffffffff81a82a2d: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ab9bd0)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81ab9bd0-ffffffff81ab9c3d: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f7778)
Location: lib/vsprintf.c:669
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff815f5250-ffffffff815f5306: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161be42)
Location: lib/vsprintf.c:672
Inline: True
Inline callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff816198d0-ffffffff81619986: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fe622)
Location: lib/vsprintf.c:698
Inline: True
Inline callers:
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff815fd8f0-ffffffff815fd9a6: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166c587)
Location: lib/vsprintf.c:699
Inline: True
Inline callers:
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff8166b5c0-ffffffff8166b676: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81786738)
Location: lib/vsprintf.c:704
Inline: True
Inline callers:
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff81785480-ffffffff81785563: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82043848)
Location: lib/vsprintf.c:705
Inline: True
Inline callers:
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff820424e0-ffffffff820425c3: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c1dc8)
Location: lib/vsprintf.c:705
Inline: True
Inline callers:
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff820c0a20-ffffffff820c0b03: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219c748)
Location: lib/vsprintf.c:707
Inline: True
Inline callers:
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
Direct callers:
  - lib/vsprintf.c:fwnode_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:hex_string
```
**Symbols:**

```
ffffffff8219b350-ffffffff8219b433: check_pointer (STB_LOCAL)
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
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d94368)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffff800010d94368-ffff800010d943e0: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e9068c)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:resource_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
c0e9068c-c0e90724: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed8c50)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
c000000000ed8c50-c000000000ed8d04: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008be278)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffe0008be278-ffffffe0008be2f0: check_pointer (STB_LOCAL)
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
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a58a20)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81a58a20-ffffffff81a58a8d: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15b00)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81a15b00-ffffffff81a15b6d: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac4e10)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81ac4e10-ffffffff81ac4e7d: check_pointer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_pointer(char **buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad12e0)
Location: lib/vsprintf.c:647
Inline: False
Direct callers:
  - lib/vsprintf.c:flags_string
  - lib/vsprintf.c:rtc_str
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
  - lib/vsprintf.c:uuid_string
  - lib/vsprintf.c:escaped_string
  - lib/vsprintf.c:ip_addr_string
  - lib/vsprintf.c:mac_address_string
  - lib/vsprintf.c:hex_string
  - lib/vsprintf.c:file_dentry_name
  - lib/vsprintf.c:dentry_name
  - lib/vsprintf.c:string
```
**Symbols:**

```
ffffffff81ad12e0-ffffffff81ad134d: check_pointer (STB_LOCAL)
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
