# Function: <code>msg_add_ext_text</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t msg_add_ext_text(char *buf, size_t size, const char *text, size_t text_len, unsigned char endc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118983)
Location: kernel/printk/printk.c:564
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_add_dict_text
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_add_dict_text
  - kernel/printk/printk.c:msg_add_dict_text
```
**Symbols:**

```
ffffffff81117d80-ffffffff81117e24: msg_add_ext_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t msg_add_ext_text(char *buf, size_t size, const char *text, size_t text_len, unsigned char endc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119013)
Location: kernel/printk/printk.c:577
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_add_dict_text
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_add_dict_text
  - kernel/printk/printk.c:msg_add_dict_text
```
**Symbols:**

```
ffffffff81118450-ffffffff811184f4: msg_add_ext_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t msg_add_ext_text(char *buf, size_t size, const char *text, size_t text_len, unsigned char endc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113a2d3)
Location: kernel/printk/printk.c:572
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_add_dict_text
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_add_dict_text
  - kernel/printk/printk.c:msg_add_dict_text
```
**Symbols:**

```
ffffffff811387d0-ffffffff81138874: msg_add_ext_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t msg_add_ext_text(char *buf, size_t size, const char *text, size_t text_len, unsigned char endc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115cad2)
Location: kernel/printk/printk.c:577
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_add_dict_text
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_add_dict_text
  - kernel/printk/printk.c:msg_add_dict_text
```
**Symbols:**

```
ffffffff8115b1c0-ffffffff8115b277: msg_add_ext_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t msg_add_ext_text(char *buf, size_t size, const char *text, size_t text_len, unsigned char endc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118f5e2)
Location: kernel/printk/printk.c:658
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_add_dict_text
Direct callers:
  - kernel/printk/printk.c:msg_print_ext_body
  - kernel/printk/printk.c:msg_add_dict_text
  - kernel/printk/printk.c:msg_add_dict_text
```
**Symbols:**

```
ffffffff8118d5b0-ffffffff8118d667: msg_add_ext_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t msg_add_ext_text(char *buf, size_t size, const char *text, size_t text_len, unsigned char endc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a0e82)
Location: kernel/printk/printk.c:645
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_add_dict_text
Direct callers:
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:msg_add_dict_text
  - kernel/printk/printk.c:msg_add_dict_text
```
**Symbols:**

```
ffffffff8119ed50-ffffffff8119ee07: msg_add_ext_text (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t msg_add_ext_text(char *buf, size_t size, const char *text, size_t text_len, unsigned char endc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811aff72)
Location: kernel/printk/printk.c:645
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_add_dict_text
Direct callers:
  - kernel/printk/printk.c:printk_get_next_message
  - kernel/printk/printk.c:msg_add_dict_text
  - kernel/printk/printk.c:msg_add_dict_text
```
**Symbols:**

```
ffffffff811ae280-ffffffff811ae337: msg_add_ext_text (STB_LOCAL)
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
