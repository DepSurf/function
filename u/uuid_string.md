# Function: <code>uuid_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff813f3b80)
Location: lib/vsprintf.c:1258
Inline: False
```
**Symbols:**

```
ffffffff813f3b80-ffffffff813f3cbb: uuid_string.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81439c40)
Location: lib/vsprintf.c:1305
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81439c40-ffffffff81439d5d: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81456c20)
Location: lib/vsprintf.c:1305
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81456c20-ffffffff81456d3d: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f84a0)
Location: lib/vsprintf.c:1306
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f84a0-ffffffff818f85ca: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197ef60)
Location: lib/vsprintf.c:1308
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197ef60-ffffffff8197f08a: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819db4e0)
Location: lib/vsprintf.c:1320
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819db4e0-ffffffff819db602: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a137c0)
Location: lib/vsprintf.c:1438
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a137c0-ffffffff81a138e2: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a82eb0)
Location: lib/vsprintf.c:1611
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a82eb0-ffffffff81a82fef: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81aba0c0)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81aba0c0-ffffffff81aba1ff: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f67a0)
Location: lib/vsprintf.c:1667
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815f67a0-ffffffff815f69b7: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161ae30)
Location: lib/vsprintf.c:1670
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8161ae30-ffffffff8161b047: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815ff070)
Location: lib/vsprintf.c:1696
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815ff070-ffffffff815ff274: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166cde0)
Location: lib/vsprintf.c:1701
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8166cde0-ffffffff8166cfea: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff817870c0)
Location: lib/vsprintf.c:1687
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff817870c0-ffffffff81787318: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82044260)
Location: lib/vsprintf.c:1688
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff82044260-ffffffff820444b8: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c2870)
Location: lib/vsprintf.c:1688
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff820c2870-ffffffff820c2ac8: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219d1f0)
Location: lib/vsprintf.c:1690
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8219d1f0-ffffffff8219d448: uuid_string (STB_LOCAL)
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
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d94898)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffff800010d94898-ffff800010d949fc: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e90a50)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
c0e90a50-c0e90bd0: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed9360)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
c000000000ed9360-c000000000ed9508: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008be6d4)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffe0008be6d4-ffffffe0008be802: uuid_string (STB_LOCAL)
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
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a58f10)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a58f10-ffffffff81a5904f: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15ff0)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a15ff0-ffffffff81a1612f: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac5300)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81ac5300-ffffffff81ac543f: uuid_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *uuid_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad17d0)
Location: lib/vsprintf.c:1620
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81ad17d0-ffffffff81ad190f: uuid_string (STB_LOCAL)
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
