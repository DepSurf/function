# Function: <code>fourcc_string</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *fourcc_string(char *buf, char *end, const u32 *fourcc, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:1763
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815feaf0-ffffffff815fed59: fourcc_string (STB_LOCAL)
ffffffff81be6cbd-ffffffff81be6cd5: fourcc_string.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *fourcc_string(char *buf, char *end, const u32 *fourcc, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:1768
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8166c9a0-ffffffff8166cc09: fourcc_string (STB_LOCAL)
ffffffff81cdfb91-ffffffff81cdfba9: fourcc_string.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *fourcc_string(char *buf, char *end, const u32 *fourcc, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:1754
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81786a90-ffffffff81786d2e: fourcc_string (STB_LOCAL)
ffffffff81ea634a-ffffffff81ea6362: fourcc_string.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *fourcc_string(char *buf, char *end, const u32 *fourcc, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82043bd0)
Location: lib/vsprintf.c:1755
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff82043bd0-ffffffff82043e7d: fourcc_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *fourcc_string(char *buf, char *end, const u32 *fourcc, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c2150)
Location: lib/vsprintf.c:1755
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff820c2150-ffffffff820c248b: fourcc_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *fourcc_string(char *buf, char *end, const u32 *fourcc, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219cad0)
Location: lib/vsprintf.c:1757
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8219cad0-ffffffff8219ce0b: fourcc_string (STB_LOCAL)
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
