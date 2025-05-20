# Function: <code>print_prefix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t print_prefix(const struct printk_log *msg, bool syslog, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d7410)
Location: kernel/printk/printk.c:1056
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
```
**Symbols:**

```
ffffffff810d7410-ffffffff810d75cc: print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t print_prefix(const struct printk_log *msg, bool syslog, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dc3b0)
Location: kernel/printk/printk.c:1193
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
```
**Symbols:**

```
ffffffff810dc3b0-ffffffff810dc56b: print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t print_prefix(const struct printk_log *msg, bool syslog, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2520)
Location: kernel/printk/printk.c:1174
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
```
**Symbols:**

```
ffffffff810e2520-ffffffff810e26d8: print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t print_prefix(const struct printk_log *msg, bool syslog, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e17d0)
Location: kernel/printk/printk.c:1224
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
```
**Symbols:**

```
ffffffff810e17d0-ffffffff810e1966: print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t print_prefix(const struct printk_log *msg, bool syslog, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e9930)
Location: kernel/printk/printk.c:1223
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
```
**Symbols:**

```
ffffffff810e9930-ffffffff810e9ac6: print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t print_prefix(const struct printk_log *msg, bool syslog, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f1c00)
Location: kernel/printk/printk.c:1227
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
  - kernel/printk/printk.c:msg_print_text
```
**Symbols:**

```
ffffffff810f1c00-ffffffff810f1d96: print_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd2dd)
Location: kernel/printk/printk.c:1243
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811059de)
Location: kernel/printk/printk.c:1278
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81111d5e)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
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
In kernel/printk/printk.c (ffffffff8111d44e)
Location: kernel/printk/printk.c:1316
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010172110)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c5bd8)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cb1c8)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010e4ce)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110a33e)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fb21e)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110822e)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811135ce)
Location: kernel/printk/printk.c:1288
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
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
</ul>
