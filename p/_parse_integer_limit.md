# Function: <code>_parse_integer_limit</code>

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
unsigned int _parse_integer_limit(const char *s, unsigned int base, long long unsigned int *p, size_t max_chars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b8e19)
Location: lib/kstrtox.c:49
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
Direct callers:
  - lib/vsprintf.c:simple_strtoll
```
**Symbols:**

```
ffffffff815b9c10-ffffffff815b9ca6: _parse_integer_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int _parse_integer_limit(const char *s, unsigned int base, long long unsigned int *p, size_t max_chars);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161f669)
Location: lib/kstrtox.c:50
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
Direct callers:
  - lib/vsprintf.c:simple_strtoll
  - lib/vsprintf.c:simple_strtoull
```
**Symbols:**

```
ffffffff81620560-ffffffff816205f6: _parse_integer_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int _parse_integer_limit(const char *s, unsigned int base, long long unsigned int *p, size_t max_chars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816edb20)
Location: lib/kstrtox.c:52
Inline: False
Direct callers:
  - lib/kstrtox.c:_parse_integer
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff816edb20-ffffffff816edbce: _parse_integer_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int _parse_integer_limit(const char *s, unsigned int base, long long unsigned int *p, size_t max_chars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817de560)
Location: lib/kstrtox.c:52
Inline: False
Direct callers:
  - lib/kstrtox.c:_parse_integer
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff817de560-ffffffff817de60e: _parse_integer_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int _parse_integer_limit(const char *s, unsigned int base, long long unsigned int *p, size_t max_chars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181dd40)
Location: lib/kstrtox.c:52
Inline: False
Direct callers:
  - lib/kstrtox.c:_parse_integer
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff8181dd40-ffffffff8181ddee: _parse_integer_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int _parse_integer_limit(const char *s, unsigned int base, long long unsigned int *p, size_t max_chars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81863bb0)
Location: lib/kstrtox.c:52
Inline: False
Direct callers:
  - lib/kstrtox.c:_parse_integer
  - lib/vsprintf.c:simple_strntoull
```
**Symbols:**

```
ffffffff81863bb0-ffffffff81863c5e: _parse_integer_limit (STB_GLOBAL)
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
