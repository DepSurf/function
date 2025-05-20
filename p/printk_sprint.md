# Function: <code>printk_sprint</code>

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
u16 printk_sprint(char *text, u16 size, int facility, enum log_flags *lflags, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118060)
Location: kernel/printk/printk.c:1931
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81118060-ffffffff811180ec: printk_sprint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 printk_sprint(char *text, u16 size, int facility, enum log_flags *lflags, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118730)
Location: kernel/printk/printk.c:2007
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81118730-ffffffff811187bc: printk_sprint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 printk_sprint(char *text, u16 size, int facility, enum printk_info_flags *flags, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113b4f0)
Location: kernel/printk/printk.c:2069
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff8113b4f0-ffffffff8113b57c: printk_sprint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 printk_sprint(char *text, u16 size, int facility, enum printk_info_flags *flags, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115e580)
Location: kernel/printk/printk.c:2086
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff8115e580-ffffffff8115e6bd: printk_sprint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 printk_sprint(char *text, u16 size, int facility, enum printk_info_flags *flags, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811914b0)
Location: kernel/printk/printk.c:2174
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff811914b0-ffffffff811915ed: printk_sprint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 printk_sprint(char *text, u16 size, int facility, enum printk_info_flags *flags, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a2db0)
Location: kernel/printk/printk.c:2122
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff811a2db0-ffffffff811a2e9d: printk_sprint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 printk_sprint(char *text, u16 size, int facility, enum printk_info_flags *flags, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b0c70)
Location: kernel/printk/printk.c:2118
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff811b0c70-ffffffff811b0d5d: printk_sprint (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum printk_info_flags *flags</code>
</li>
<li>
<b>Param removed. </b>
<code>enum log_flags *lflags</code>
</li>
</ul>
</details>
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
