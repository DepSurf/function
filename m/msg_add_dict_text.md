# Function: <code>msg_add_dict_text</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t msg_add_dict_text(char *buf, size_t size, const char *key, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118940)
Location: kernel/printk/printk.c:585
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_print_ext_body
```
**Symbols:**

```
ffffffff81118940-ffffffff81118a10: msg_add_dict_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t msg_add_dict_text(char *buf, size_t size, const char *key, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118fd0)
Location: kernel/printk/printk.c:598
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_print_ext_body
```
**Symbols:**

```
ffffffff81118fd0-ffffffff8111909d: msg_add_dict_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t msg_add_dict_text(char *buf, size_t size, const char *key, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113a290)
Location: kernel/printk/printk.c:593
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_print_ext_body
```
**Symbols:**

```
ffffffff8113a290-ffffffff8113a35d: msg_add_dict_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t msg_add_dict_text(char *buf, size_t size, const char *key, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115ca80)
Location: kernel/printk/printk.c:598
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_print_ext_body
```
**Symbols:**

```
ffffffff8115ca80-ffffffff8115cb73: msg_add_dict_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t msg_add_dict_text(char *buf, size_t size, const char *key, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118f590)
Location: kernel/printk/printk.c:679
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_print_ext_body
```
**Symbols:**

```
ffffffff8118f590-ffffffff8118f683: msg_add_dict_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t msg_add_dict_text(char *buf, size_t size, const char *key, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a0e30)
Location: kernel/printk/printk.c:666
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:printk_get_next_message
```
**Symbols:**

```
ffffffff811a0e30-ffffffff811a0f23: msg_add_dict_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t msg_add_dict_text(char *buf, size_t size, const char *key, const char *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811aff20)
Location: kernel/printk/printk.c:666
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:printk_get_next_message
```
**Symbols:**

```
ffffffff811aff20-ffffffff811b0013: msg_add_dict_text (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
