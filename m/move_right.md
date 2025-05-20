# Function: <code>move_right</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81439943)
Location: lib/vsprintf.c:535
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81456923)
Location: lib/vsprintf.c:535
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f8173)
Location: lib/vsprintf.c:536
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197ec33)
Location: lib/vsprintf.c:538
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff819db1bf)
Location: lib/vsprintf.c:547
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a1349f)
Location: lib/vsprintf.c:548
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81a82910)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81ab9b20)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff815f474b)
Location: lib/vsprintf.c:553
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81618dbb)
Location: lib/vsprintf.c:556
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff815fc43b)
Location: lib/vsprintf.c:582
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81669a7b)
Location: lib/vsprintf.c:583
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void move_right(char *buf, char *end, unsigned int len, unsigned int spaces);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff817835b0)
Location: lib/vsprintf.c:588
Inline: False
Direct callers:
  - lib/vsprintf.c:widen_string
```
**Symbols:**

```
ffffffff817835b0-ffffffff8178363d: move_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void move_right(char *buf, char *end, unsigned int len, unsigned int spaces);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820410e0)
Location: lib/vsprintf.c:589
Inline: False
Direct callers:
  - lib/vsprintf.c:widen_string
```
**Symbols:**

```
ffffffff820410e0-ffffffff8204116d: move_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void move_right(char *buf, char *end, unsigned int len, unsigned int spaces);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820bf5f0)
Location: lib/vsprintf.c:589
Inline: False
Direct callers:
  - lib/vsprintf.c:widen_string
```
**Symbols:**

```
ffffffff820bf5f0-ffffffff820bf67d: move_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void move_right(char *buf, char *end, unsigned int len, unsigned int spaces);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219a8a0)
Location: lib/vsprintf.c:591
Inline: False
Direct callers:
  - lib/vsprintf.c:widen_string
```
**Symbols:**

```
ffffffff8219a8a0-ffffffff8219a92d: move_right (STB_LOCAL)
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
In lib/vsprintf.c (ffff800010d9428c)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (c0e905b4)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (c000000000ed8b48)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffe0008be1c4)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81a58970)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81a15a50)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81ac4d60)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
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
In lib/vsprintf.c (ffffffff81ad1230)
Location: lib/vsprintf.c:550
Inline: True
Inline callers:
  - lib/vsprintf.c:widen_string
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
