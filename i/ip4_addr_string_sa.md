# Function: <code>ip4_addr_string_sa</code>

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
In lib/vsprintf.c (ffffffff813f4990)
Location: lib/vsprintf.c:1163
Inline: False
```
**Symbols:**

```
ffffffff813f4990-ffffffff813f4ac7: ip4_addr_string_sa.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143a6c0)
Location: lib/vsprintf.c:1210
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8143a6c0-ffffffff8143a7dd: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff814576a0)
Location: lib/vsprintf.c:1210
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff814576a0-ffffffff814577bd: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f8f60)
Location: lib/vsprintf.c:1211
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f8f60-ffffffff818f9076: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197fa30)
Location: lib/vsprintf.c:1213
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197fa30-ffffffff8197fb46: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dbc30)
Location: lib/vsprintf.c:1225
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819dbc30-ffffffff819dbd4e: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a13f30)
Location: lib/vsprintf.c:1343
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a13f30-ffffffff81a1404e: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a83560)
Location: lib/vsprintf.c:1467
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a83560-ffffffff81a83698: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81aba7d0)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81aba7d0-ffffffff81aba908: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f50b0)
Location: lib/vsprintf.c:1523
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815f50b0-ffffffff815f5243: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81619730)
Location: lib/vsprintf.c:1526
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81619730-ffffffff816198c3: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd760)
Location: lib/vsprintf.c:1552
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815fd760-ffffffff815fd8f0: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166b430)
Location: lib/vsprintf.c:1557
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8166b430-ffffffff8166b5c0: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff817852c0)
Location: lib/vsprintf.c:1543
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff817852c0-ffffffff81785471: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82042310)
Location: lib/vsprintf.c:1544
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff82042310-ffffffff820424c1: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c0850)
Location: lib/vsprintf.c:1544
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff820c0850-ffffffff820c0a01: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219b180)
Location: lib/vsprintf.c:1546
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8219b180-ffffffff8219b331: ip4_addr_string_sa (STB_LOCAL)
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
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d94a00)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffff800010d94a00-ffff800010d94b68: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e92224)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c0e92224-c0e923d4: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed9d80)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c000000000ed9d80-c000000000ed9f8c: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008beca0)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffe0008beca0-ffffffe0008bedc2: ip4_addr_string_sa (STB_LOCAL)
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
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a59620)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a59620-ffffffff81a59758: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a16700)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a16700-ffffffff81a16838: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac5a10)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ac5a10-ffffffff81ac5b48: ip4_addr_string_sa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *ip4_addr_string_sa(char *buf, char *end, const struct sockaddr_in *sa, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad1ce0)
Location: lib/vsprintf.c:1476
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ad1ce0-ffffffff81ad1e18: ip4_addr_string_sa (STB_LOCAL)
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
