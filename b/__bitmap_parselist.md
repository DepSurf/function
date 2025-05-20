# Function: <code>__bitmap_parselist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __bitmap_parselist(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9960)
Location: lib/bitmap.c:504
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff813f9960-ffffffff813f9b02: __bitmap_parselist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __bitmap_parselist(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440990)
Location: lib/bitmap.c:506
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff81440990-ffffffff81440b41: __bitmap_parselist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bitmap_parselist(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145da90)
Location: lib/bitmap.c:511
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff8145da90-ffffffff8145dd6f: __bitmap_parselist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bitmap_parselist(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814629e0)
Location: lib/bitmap.c:511
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff814629e0-ffffffff81462cbe: __bitmap_parselist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bitmap_parselist(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e8d0)
Location: lib/bitmap.c:513
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff8148e8d0-ffffffff8148ebd0: __bitmap_parselist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bitmap_parselist(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c36b0)
Location: lib/bitmap.c:510
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff814c36b0-ffffffff814c39ba: __bitmap_parselist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bitmap_parselist(const char *buf, unsigned int buflen, int is_user, long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7ae0)
Location: lib/bitmap.c:505
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff814d7ae0-ffffffff814d7dea: __bitmap_parselist (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
