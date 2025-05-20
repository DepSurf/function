# Function: <code>rtc_str</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15510)
Location: lib/vsprintf.c:1603
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff81a15510-ffffffff81a15567: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a84f40)
Location: lib/vsprintf.c:1737
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff81a84f40-ffffffff81a84fe7: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abc1b0)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff81abc1b0-ffffffff81abc257: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f5e00)
Location: lib/vsprintf.c:1793
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff815f5e00-ffffffff815f5f05: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161a480)
Location: lib/vsprintf.c:1797
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff8161a480-ffffffff8161a585: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fe610)
Location: lib/vsprintf.c:1859
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff815fe610-ffffffff815fe711: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166c570)
Location: lib/vsprintf.c:1864
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff8166c570-ffffffff8166c6e2: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81786720)
Location: lib/vsprintf.c:1852
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff81786720-ffffffff817868c7: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82043830)
Location: lib/vsprintf.c:1853
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff82043830-ffffffff820439d7: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c1db0)
Location: lib/vsprintf.c:1853
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff820c1db0-ffffffff820c1f5f: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219c730)
Location: lib/vsprintf.c:1855
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:time64_str
```
**Symbols:**

```
ffffffff8219c730-ffffffff8219c8df: rtc_str (STB_LOCAL)
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
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d95e50)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffff800010d95e50-ffff800010d95f24: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e93908)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
c0e93908-c0e939d4: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000edb3e0)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
c000000000edb3e0-c000000000edb500: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bf98a)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffe0008bf98a-ffffffe0008bfa4e: rtc_str (STB_LOCAL)
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
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5b000)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff81a5b000-ffffffff81a5b0a7: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a180e0)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff81a180e0-ffffffff81a18187: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac73f0)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff81ac73f0-ffffffff81ac7497: rtc_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *rtc_str(char *buf, char *end, const struct rtc_time *tm, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad38d0)
Location: lib/vsprintf.c:1746
Inline: False
Direct callers:
  - lib/vsprintf.c:time_and_date
```
**Symbols:**

```
ffffffff81ad38d0-ffffffff81ad3977: rtc_str (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct printf_spec spec</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, end, tm, fmt</code> ➡️ <code>buf, end, tm, spec, fmt</code>
</li>
</ul>
</details>
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
