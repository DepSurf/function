# Function: <code>ip4_addr_string</code>

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
In lib/vsprintf.c (ffffffff813f3b00)
Location: lib/vsprintf.c:1090
Inline: False
```
**Symbols:**

```
ffffffff813f3b00-ffffffff813f3b76: ip4_addr_string.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81439bd0)
Location: lib/vsprintf.c:1137
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81439bd0-ffffffff81439c35: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81456bb0)
Location: lib/vsprintf.c:1137
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81456bb0-ffffffff81456c15: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f8430)
Location: lib/vsprintf.c:1138
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f8430-ffffffff818f8495: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197eef0)
Location: lib/vsprintf.c:1140
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197eef0-ffffffff8197ef55: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819db470)
Location: lib/vsprintf.c:1152
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819db470-ffffffff819db4d5: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a13750)
Location: lib/vsprintf.c:1270
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a13750-ffffffff81a137b5: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a82e40)
Location: lib/vsprintf.c:1394
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a82e40-ffffffff81a82ea7: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81aba050)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81aba050-ffffffff81aba0b7: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f4e80)
Location: lib/vsprintf.c:1450
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815f4e80-ffffffff815f4f20: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81619500)
Location: lib/vsprintf.c:1453
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81619500-ffffffff816195a0: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd530)
Location: lib/vsprintf.c:1479
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff815fd530-ffffffff815fd5d0: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166b190)
Location: lib/vsprintf.c:1484
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8166b190-ffffffff8166b230: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81784fb0)
Location: lib/vsprintf.c:1470
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81784fb0-ffffffff8178506b: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82041fd0)
Location: lib/vsprintf.c:1471
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff82041fd0-ffffffff8204208b: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c0510)
Location: lib/vsprintf.c:1471
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff820c0510-ffffffff820c05cb: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219ae40)
Location: lib/vsprintf.c:1473
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff8219ae40-ffffffff8219aefb: ip4_addr_string (STB_LOCAL)
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
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d94820)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffff800010d94820-ffff800010d94894: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e909cc)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c0e909cc-c0e90a50: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed92d0)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
c000000000ed92d0-c000000000ed935c: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008be68e)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffe0008be68e-ffffffe0008be6d4: ip4_addr_string (STB_LOCAL)
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
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a58ea0)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a58ea0-ffffffff81a58f07: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15f80)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81a15f80-ffffffff81a15fe7: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac5290)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ac5290-ffffffff81ac52f7: ip4_addr_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *ip4_addr_string(char *buf, char *end, const u8 *addr, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad1760)
Location: lib/vsprintf.c:1403
Inline: False
Direct callers:
  - lib/vsprintf.c:ip_addr_string
```
**Symbols:**

```
ffffffff81ad1760-ffffffff81ad17c7: ip4_addr_string (STB_LOCAL)
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
