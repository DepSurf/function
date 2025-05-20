# Function: <code>dentry_name</code>

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
In lib/vsprintf.c (ffffffff813f3f20)
Location: lib/vsprintf.c:560
Inline: False
```
**Symbols:**

```
ffffffff813f3f20-ffffffff813f40bb: dentry_name.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81439ea0)
Location: lib/vsprintf.c:604
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81439ea0-ffffffff81439f97: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81456e80)
Location: lib/vsprintf.c:604
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81456e80-ffffffff81456f77: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f8700)
Location: lib/vsprintf.c:605
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f8700-ffffffff818f8834: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197f1d0)
Location: lib/vsprintf.c:607
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197f1d0-ffffffff8197f304: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819db750)
Location: lib/vsprintf.c:616
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819db750-ffffffff819db886: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a13a30)
Location: lib/vsprintf.c:720
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a13a30-ffffffff81a13b74: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a82ff0)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a82ff0-ffffffff81a83181: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81aba200)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff81aba200-ffffffff81aba391: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f4c60)
Location: lib/vsprintf.c:871
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff815f4c60-ffffffff815f4e71: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff816192d0)
Location: lib/vsprintf.c:874
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff816192d0-ffffffff816194ff: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd2f0)
Location: lib/vsprintf.c:900
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff815fd2f0-ffffffff815fd52a: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166ae50)
Location: lib/vsprintf.c:901
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff8166ae50-ffffffff8166b184: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81784c20)
Location: lib/vsprintf.c:897
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff81784c20-ffffffff81784fa7: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82041c30)
Location: lib/vsprintf.c:898
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff82041c30-ffffffff82041fb7: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c0190)
Location: lib/vsprintf.c:898
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff820c0190-ffffffff820c04fc: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219aac0)
Location: lib/vsprintf.c:900
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff8219aac0-ffffffff8219ae2c: dentry_name (STB_LOCAL)
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
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d94b68)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffff800010d94b68-ffff800010d94ce4: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e90bd0)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
c0e90bd0-c0e90d68: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ed9510)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
c000000000ed9510-c000000000ed9768: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008be802)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffe0008be802-ffffffe0008be94e: dentry_name (STB_LOCAL)
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
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a59050)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff81a59050-ffffffff81a591e1: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a16130)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff81a16130-ffffffff81a162c1: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac5440)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff81ac5440-ffffffff81ac55d1: dentry_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *dentry_name(char *buf, char *end, const struct dentry *d, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad22c0)
Location: lib/vsprintf.c:824
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:file_dentry_name
```
**Symbols:**

```
ffffffff81ad22c0-ffffffff81ad246f: dentry_name (STB_LOCAL)
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
