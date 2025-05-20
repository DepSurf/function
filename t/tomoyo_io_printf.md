# Function: <code>tomoyo_io_printf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813688f0)
Location: security/tomoyo/common.c:274
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_config
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
```
**Symbols:**

```
ffffffff813688f0-ffffffff813689c5: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8139e7e0)
Location: security/tomoyo/common.c:274
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff8139e7e0-ffffffff8139e8b5: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813b53b0)
Location: security/tomoyo/common.c:274
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff813b53b0-ffffffff813b5485: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813cbd30)
Location: security/tomoyo/common.c:274
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff813cbd30-ffffffff813cbdf4: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f21d0)
Location: security/tomoyo/common.c:275
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff813f21d0-ffffffff813f2294: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81423050)
Location: security/tomoyo/common.c:275
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff81423050-ffffffff81423116: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8143f6b0)
Location: security/tomoyo/common.c:275
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff8143f6b0-ffffffff8143f776: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff8146d2e0-ffffffff8146d3a9: tomoyo_io_printf (STB_LOCAL)
ffffffff814707f2-ffffffff81470805: tomoyo_io_printf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814870e0)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff814870e0-ffffffff814871a9: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814dded0)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff814dded0-ffffffff814ddfb4: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814fb2f0)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff814fb2f0-ffffffff814fb3d4: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81501aa0)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff81501aa0-ffffffff81501b84: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8155d120)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff8155d120-ffffffff8155d226: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff815f8600)
Location: security/tomoyo/common.c:268
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff815f8600-ffffffff815f8730: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816a9280)
Location: security/tomoyo/common.c:268
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff816a9280-ffffffff816a93b0: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816e1cc0)
Location: security/tomoyo/common.c:268
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff816e1cc0-ffffffff816e1df0: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8171e970)
Location: security/tomoyo/common.c:269
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/common.c:tomoyo_select_domain
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
```
**Symbols:**

```
ffffffff8171e970-ffffffff8171eaa0: tomoyo_io_printf (STB_LOCAL)
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
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffff800010579750)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffff800010579750-ffff800010579844: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c072cd6c)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
c072cd6c-c072ce3c: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c0000000006e3d00)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
c0000000006e3d00-c0000000006e3de4: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffe0003cb948)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffe0003cb948-ffffffe0003cb9de: tomoyo_io_printf (STB_LOCAL)
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
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147f6c0)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff8147f6c0-ffffffff8147f789: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814700e0)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff814700e0-ffffffff814701a9: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147b760)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff8147b760-ffffffff8147b829: tomoyo_io_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tomoyo_io_printf(struct tomoyo_io_buffer *head, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81493840)
Location: security/tomoyo/common.c:277
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_group
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_print_entry
  - security/tomoyo/common.c:tomoyo_set_group
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
  - security/tomoyo/common.c:tomoyo_print_config
```
**Symbols:**

```
ffffffff81493840-ffffffff81493909: tomoyo_io_printf (STB_LOCAL)
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
