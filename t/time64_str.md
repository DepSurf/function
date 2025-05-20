# Function: <code>time64_str</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f5f10)
Location: lib/vsprintf.c:1831
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff815f5f10-ffffffff815f5faa: time64_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161a590)
Location: lib/vsprintf.c:1835
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff8161a590-ffffffff8161a62a: time64_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fe720)
Location: lib/vsprintf.c:1897
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff815fe720-ffffffff815fe7ba: time64_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166c6f0)
Location: lib/vsprintf.c:1914
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff8166c6f0-ffffffff8166c78a: time64_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff817868d0)
Location: lib/vsprintf.c:1902
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff817868d0-ffffffff817869a1: time64_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820439f0)
Location: lib/vsprintf.c:1903
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff820439f0-ffffffff82043ac1: time64_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c1f70)
Location: lib/vsprintf.c:1903
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff820c1f70-ffffffff820c2041: time64_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *time64_str(char *buf, char *end, const time64_t time, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219c8f0)
Location: lib/vsprintf.c:1905
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff8219c8f0-ffffffff8219c9c1: time64_str (STB_LOCAL)
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
