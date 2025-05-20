# Function: <code>split</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd7a0)
Location: drivers/xen/xenbus/xenbus_xs.c:367
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_xs.c:process_msg
```
**Symbols:**

```
ffffffff814cd7a0-ffffffff814cd8a2: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e320)
Location: drivers/xen/xenbus/xenbus_xs.c:362
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8151e320-ffffffff8151e41a: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a7a0)
Location: drivers/xen/xenbus/xenbus_xs.c:362
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8154a7a0-ffffffff8154a89a: split (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155ed83)
Location: drivers/xen/xenbus/xenbus_xs.c:388
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c30b3)
Location: drivers/xen/xenbus/xenbus_xs.c:391
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fb775)
Location: drivers/xen/xenbus/xenbus_xs.c:393
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616825)
Location: drivers/xen/xenbus/xenbus_xs.c:393
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164a4b4)
Location: drivers/xen/xenbus/xenbus_xs.c:396
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166c944)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c050)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8171c050-ffffffff8171c101: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739000)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81739000-ffffffff817390b1: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171ca20)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8171ca20-ffffffff8171cad1: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179b790)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8179b790-ffffffff8179b841: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d4d70)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff818d4d70-ffffffff818d4e2b: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a27280)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81a27280-ffffffff81a2733b: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a708f0)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81a708f0-ffffffff81a70a58: split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char **split(char *strings, unsigned int len, unsigned int *num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac29f0)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81ac29f0-ffffffff81ac2b58: split (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_xs.c (ffff800010836fe0)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816327b4)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660784)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167ad64)
Location: drivers/xen/xenbus/xenbus_xs.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
</details>
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
