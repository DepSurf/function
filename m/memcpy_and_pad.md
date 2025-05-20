# Function: <code>memcpy_and_pad</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memcpy_and_pad(void *dest, size_t dest_len, const void *src, size_t count, int pad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8161ee20)
Location: lib/string_helpers.c:708
Inline: False
```
**Symbols:**

```
ffffffff8161ee20-ffffffff8161ee6c: memcpy_and_pad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memcpy_and_pad(void *dest, size_t dest_len, const void *src, size_t count, int pad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff816ece20)
Location: lib/string_helpers.c:961
Inline: False
```
**Symbols:**

```
ffffffff816ece20-ffffffff816ece8e: memcpy_and_pad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memcpy_and_pad(void *dest, size_t dest_len, const void *src, size_t count, int pad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff817dd750)
Location: lib/string_helpers.c:1005
Inline: False
```
**Symbols:**

```
ffffffff817dd750-ffffffff817dd7be: memcpy_and_pad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memcpy_and_pad(void *dest, size_t dest_len, const void *src, size_t count, int pad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8181cf60)
Location: lib/string_helpers.c:1009
Inline: False
```
**Symbols:**

```
ffffffff8181cf60-ffffffff8181cfce: memcpy_and_pad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memcpy_and_pad(void *dest, size_t dest_len, const void *src, size_t count, int pad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81862dd0)
Location: lib/string_helpers.c:1026
Inline: False
```
**Symbols:**

```
ffffffff81862dd0-ffffffff81862e3e: memcpy_and_pad (STB_GLOBAL)
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
