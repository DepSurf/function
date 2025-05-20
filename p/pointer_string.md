# Function: <code>pointer_string</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
char *pointer_string(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197e600)
Location: lib/vsprintf.c:1650
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197e600-ffffffff8197e679: pointer_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *pointer_string(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dab30)
Location: lib/vsprintf.c:1361
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
```
**Symbols:**

```
ffffffff819dab30-ffffffff819daba1: pointer_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *pointer_string(char *buf, char *end, const void *ptr, struct printf_spec spec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a12ba0)
Location: lib/vsprintf.c:617
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
**Symbols:**

```
ffffffff81a12ba0-ffffffff81a12c11: pointer_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a851d6)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abc446)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f834c)
Location: lib/vsprintf.c:693
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161ca0c)
Location: lib/vsprintf.c:696
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8160023a)
Location: lib/vsprintf.c:722
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166e15c)
Location: lib/vsprintf.c:723
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
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
In lib/vsprintf.c (ffffffff81788419)
Location: lib/vsprintf.c:728
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
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
In lib/vsprintf.c (ffffffff82045766)
Location: lib/vsprintf.c:729
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
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
In lib/vsprintf.c (ffffffff820c3fb5)
Location: lib/vsprintf.c:729
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
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
In lib/vsprintf.c (ffffffff8219e935)
Location: lib/vsprintf.c:731
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:default_pointer
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d96914)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e9407c)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000edcc80)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008c09dc)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5b296)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a18376)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac7686)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad3b66)
Location: lib/vsprintf.c:671
Inline: True
Inline callers:
  - lib/vsprintf.c:pointer
  - lib/vsprintf.c:restricted_pointer
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
