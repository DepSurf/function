# Function: <code>ip6_addr_string</code>

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
In lib/vsprintf.c (ffffffff813f3d90)
Location: lib/vsprintf.c:1076
Inline: False
```
**Symbols:**

```
ffffffff813f3d90-ffffffff813f3e35: ip6_addr_string.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143a630)
Location: lib/vsprintf.c:1123
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8143a630-ffffffff8143a6b2: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81457610)
Location: lib/vsprintf.c:1123
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81457610-ffffffff81457692: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f8ed0)
Location: lib/vsprintf.c:1124
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f8ed0-ffffffff818f8f52: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197f9a0)
Location: lib/vsprintf.c:1126
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197f9a0-ffffffff8197fa22: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dbba0)
Location: lib/vsprintf.c:1138
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819dbba0-ffffffff819dbc22: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a13ea0)
Location: lib/vsprintf.c:1256
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a13ea0-ffffffff81a13f22: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a834d0)
Location: lib/vsprintf.c:1380
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a834d0-ffffffff81a83551: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81aba740)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81aba740-ffffffff81aba7c1: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f4f20)
Location: lib/vsprintf.c:1436
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815f4f20-ffffffff815f4fd8: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff816195a0)
Location: lib/vsprintf.c:1439
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff816195a0-ffffffff81619658: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd5d0)
Location: lib/vsprintf.c:1465
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815fd5d0-ffffffff815fd688: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166b230)
Location: lib/vsprintf.c:1470
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8166b230-ffffffff8166b2e8: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81785070)
Location: lib/vsprintf.c:1456
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81785070-ffffffff81785158: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820420a0)
Location: lib/vsprintf.c:1457
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff820420a0-ffffffff82042188: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c05e0)
Location: lib/vsprintf.c:1457
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff820c05e0-ffffffff820c06c8: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219af10)
Location: lib/vsprintf.c:1459
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8219af10-ffffffff8219aff8: ip6_addr_string (STB_LOCAL)
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
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d95018)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffff800010d95018-ffff800010d950c0: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e91184)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c0e91184-c0e91234: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed9cb0)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c000000000ed9cb0-c000000000ed9d80: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bec34)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffe0008bec34-ffffffe0008beca0: ip6_addr_string (STB_LOCAL)
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
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a59590)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a59590-ffffffff81a59611: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a16670)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a16670-ffffffff81a166f1: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac5980)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ac5980-ffffffff81ac5a01: ip6_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *ip6_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad1c50)
Location: lib/vsprintf.c:1389
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ad1c50-ffffffff81ad1cd1: ip6_addr_string (STB_LOCAL)
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
