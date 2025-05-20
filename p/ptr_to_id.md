# Function: <code>ptr_to_id</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81981115)
Location: lib/vsprintf.c:1698
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dd1ad)
Location: lib/vsprintf.c:1693
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a14430)
Location: lib/vsprintf.c:688
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:time_and_date
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81a14430-ffffffff81a144b6: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a83b40)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81a83b40-ffffffff81a83cd4: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abadb0)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81abadb0-ffffffff81abaf44: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f69c0)
Location: lib/vsprintf.c:791
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff815f69c0-ffffffff815f6c27: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161b9e0)
Location: lib/vsprintf.c:794
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff8161b9e0-ffffffff8161bc47: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815ff280)
Location: lib/vsprintf.c:820
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff815ff280-ffffffff815ff4e5: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166cff0)
Location: lib/vsprintf.c:821
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff8166cff0-ffffffff8166d255: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81787382)
Location: lib/vsprintf.c:804
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82044527)
Location: lib/vsprintf.c:805
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c2b24)
Location: lib/vsprintf.c:805
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219d4a4)
Location: lib/vsprintf.c:807
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
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
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d95b60)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffff800010d95b60-ffff800010d95c64: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e92d2c)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
c0e92d2c-c0e92e70: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000edaf50)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
c000000000edaf50-c000000000edb130: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bf6a2)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffe0008bf6a2-ffffffe0008bf7ba: ptr_to_id (STB_LOCAL)
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
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a59c00)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81a59c00-ffffffff81a59d94: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a16ce0)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81a16ce0-ffffffff81a16e74: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac5ff0)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81ac5ff0-ffffffff81ac6184: ptr_to_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *ptr_to_id(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad24d0)
Location: lib/vsprintf.c:743
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff81ad24d0-ffffffff81ad2664: ptr_to_id (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
