# Function: <code>ip6_addr_string_sa</code>

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
In lib/vsprintf.c (ffffffff813f4ad0)
Location: lib/vsprintf.c:1101
Inline: False
```
**Symbols:**

```
ffffffff813f4ad0-ffffffff813f4cfa: ip6_addr_string_sa.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143a7e0)
Location: lib/vsprintf.c:1148
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8143a7e0-ffffffff8143a9b0: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff814577c0)
Location: lib/vsprintf.c:1148
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff814577c0-ffffffff81457990: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f9080)
Location: lib/vsprintf.c:1149
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f9080-ffffffff818f9265: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197fb50)
Location: lib/vsprintf.c:1151
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197fb50-ffffffff8197fd35: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dbd50)
Location: lib/vsprintf.c:1163
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819dbd50-ffffffff819dbf37: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a14050)
Location: lib/vsprintf.c:1281
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a14050-ffffffff81a14237: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a836a0)
Location: lib/vsprintf.c:1405
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a836a0-ffffffff81a838c6: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81aba910)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81aba910-ffffffff81abab36: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f56b0)
Location: lib/vsprintf.c:1461
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815f56b0-ffffffff815f5945: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81619d30)
Location: lib/vsprintf.c:1464
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81619d30-ffffffff81619fc5: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fde30)
Location: lib/vsprintf.c:1490
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815fde30-ffffffff815fe0a6: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166bb00)
Location: lib/vsprintf.c:1495
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8166bb00-ffffffff8166bd76: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81785ae0)
Location: lib/vsprintf.c:1481
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81785ae0-ffffffff81785da8: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82042b40)
Location: lib/vsprintf.c:1482
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff82042b40-ffffffff82042e25: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c10c0)
Location: lib/vsprintf.c:1482
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff820c10c0-ffffffff820c13c4: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219b9f0)
Location: lib/vsprintf.c:1484
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8219b9f0-ffffffff8219bcf4: ip6_addr_string_sa (STB_LOCAL)
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
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d950c0)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffff800010d950c0-ffff800010d952cc: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e923d4)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c0e923d4-c0e9269c: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed9f90)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c000000000ed9f90-c000000000eda268: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bedc2)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffe0008bedc2-ffffffe0008befaa: ip6_addr_string_sa (STB_LOCAL)
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
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a59760)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a59760-ffffffff81a59986: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a16840)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a16840-ffffffff81a16a66: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac5b50)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ac5b50-ffffffff81ac5d76: ip6_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *ip6_addr_string_sa(char *buf, char *end, const struct sockaddr_in6 *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad1e20)
Location: lib/vsprintf.c:1414
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ad1e20-ffffffff81ad2046: ip6_addr_string_sa (STB_LOCAL)
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
