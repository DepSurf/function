# Function: <code>kfree_strarray</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kfree_strarray(char **array, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff815ad650)
Location: lib/string_helpers.c:663
Inline: True
```
**Symbols:**

```
ffffffff815ad650-ffffffff815ad691: kfree_strarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kfree_strarray(char **array, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff815b82f0)
Location: lib/string_helpers.c:663
Inline: True
```
**Symbols:**

```
ffffffff815b82f0-ffffffff815b8331: kfree_strarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kfree_strarray(char **array, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8161ee70)
Location: lib/string_helpers.c:687
Inline: True
```
**Symbols:**

```
ffffffff8161ee70-ffffffff8161eeb1: kfree_strarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kfree_strarray(char **array, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff816ed07b)
Location: lib/string_helpers.c:721
Inline: True
Inline callers:
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:kasprintf_strarray
  - lib/string_helpers.c:kasprintf_strarray
```
**Symbols:**

```
ffffffff816ed010-ffffffff816ed065: kfree_strarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kfree_strarray(char **array, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff817dd84b)
Location: lib/string_helpers.c:765
Inline: True
Inline callers:
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:kasprintf_strarray
  - lib/string_helpers.c:kasprintf_strarray
```
**Symbols:**

```
ffffffff817dd7d0-ffffffff817dd825: kfree_strarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kfree_strarray(char **array, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8181d05b)
Location: lib/string_helpers.c:765
Inline: True
Inline callers:
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:kasprintf_strarray
  - lib/string_helpers.c:kasprintf_strarray
```
**Symbols:**

```
ffffffff8181cfe0-ffffffff8181d035: kfree_strarray (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kfree_strarray(char **array, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81862ecb)
Location: lib/string_helpers.c:782
Inline: True
Inline callers:
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:devm_kfree_strarray
  - lib/string_helpers.c:kasprintf_strarray
  - lib/string_helpers.c:kasprintf_strarray
```
**Symbols:**

```
ffffffff81862e50-ffffffff81862ea5: kfree_strarray (STB_GLOBAL)
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
