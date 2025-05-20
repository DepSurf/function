# Function: <code>simple_strntoull</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int simple_strntoull(const char *startp, size_t max_chars, char **endp, unsigned int base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd1ce)
Location: lib/vsprintf.c:56
Inline: True
Inline callers:
  - lib/vsprintf.c:simple_strtoll
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
```
**Symbols:**

```
ffffffff815fbe10-ffffffff815fbea9: simple_strntoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int simple_strntoull(const char *startp, size_t max_chars, char **endp, unsigned int base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166adee)
Location: lib/vsprintf.c:56
Inline: True
Inline callers:
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoull
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
```
**Symbols:**

```
ffffffff81669940-ffffffff816699d9: simple_strntoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long long unsigned int simple_strntoull(const char *startp, size_t max_chars, char **endp, unsigned int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81783490)
Location: lib/vsprintf.c:61
Inline: False
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff81783490-ffffffff81783535: simple_strntoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long long unsigned int simple_strntoull(const char *startp, size_t max_chars, char **endp, unsigned int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82040490)
Location: lib/vsprintf.c:62
Inline: False
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff82040490-ffffffff82040535: simple_strntoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long long unsigned int simple_strntoull(const char *startp, size_t max_chars, char **endp, unsigned int base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820be990)
Location: lib/vsprintf.c:62
Inline: False
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff820be990-ffffffff820bea35: simple_strntoull (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long long unsigned int simple_strntoull(const char *startp, char **endp, unsigned int base, size_t max_chars);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82199210)
Location: lib/vsprintf.c:64
Inline: False
Direct callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:simple_strntoll
  - lib/vsprintf.c:simple_strntoll
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff82199210-ffffffff821992b5: simple_strntoull (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>startp, max_chars, endp, base</code> ➡️ <code>startp, endp, base, max_chars</code>
</li>
</ul>
</details>
</li>
</ul>
