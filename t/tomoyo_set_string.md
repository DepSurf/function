# Function: <code>tomoyo_set_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813688b0)
Location: security/tomoyo/common.c:256
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
```
**Symbols:**

```
ffffffff813688b0-ffffffff813688ef: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8139e7a0)
Location: security/tomoyo/common.c:256
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff8139e7a0-ffffffff8139e7df: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813b5370)
Location: security/tomoyo/common.c:256
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff813b5370-ffffffff813b53a9: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813cbd00)
Location: security/tomoyo/common.c:256
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff813cbd00-ffffffff813cbd29: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f21a0)
Location: security/tomoyo/common.c:257
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff813f21a0-ffffffff813f21ca: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81423020)
Location: security/tomoyo/common.c:257
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff81423020-ffffffff8142304a: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8143f680)
Location: security/tomoyo/common.c:257
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff8143f680-ffffffff8143f6aa: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (ffffffff814707df)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff8146d2b0-ffffffff8146d2da: tomoyo_set_string (STB_LOCAL)
ffffffff814707df-ffffffff814707f2: tomoyo_set_string.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814870b0)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff814870b0-ffffffff814870d9: tomoyo_set_string (STB_LOCAL)
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
In security/tomoyo/common.c (ffffffff814deb25)
Location: security/tomoyo/common.c:259
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_io_printf
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
In security/tomoyo/common.c (ffffffff814fbf45)
Location: security/tomoyo/common.c:259
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_io_printf
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
In security/tomoyo/common.c (ffffffff815026f5)
Location: security/tomoyo/common.c:259
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_policy
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
  - security/tomoyo/common.c:tomoyo_io_printf
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
In security/tomoyo/common.c (ffffffff815610ad)
Location: security/tomoyo/common.c:259
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
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
In security/tomoyo/common.c (ffffffff815fc0ed)
Location: security/tomoyo/common.c:250
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
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
In security/tomoyo/common.c (ffffffff816ace5d)
Location: security/tomoyo/common.c:250
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
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
In security/tomoyo/common.c (ffffffff816e588d)
Location: security/tomoyo/common.c:250
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
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
In security/tomoyo/common.c (ffffffff8172253d)
Location: security/tomoyo/common.c:251
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
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
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffff800010579618)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffff800010579618-ffff800010579674: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c072cc70)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
c072cc70-c072ccc4: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c0000000006e3cb0)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
c0000000006e3cb0-c0000000006e3cfc: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffe0003cb8ea)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffe0003cb8ea-ffffffe0003cb948: tomoyo_set_string (STB_LOCAL)
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
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147f690)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff8147f690-ffffffff8147f6b9: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814700b0)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff814700b0-ffffffff814700d9: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147b730)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff8147b730-ffffffff8147b759: tomoyo_set_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tomoyo_set_string(struct tomoyo_io_buffer *head, const char *string);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81493810)
Location: security/tomoyo/common.c:259
Inline: True
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_exception
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_io_printf
```
**Symbols:**

```
ffffffff81493810-ffffffff81493839: tomoyo_set_string (STB_LOCAL)
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
