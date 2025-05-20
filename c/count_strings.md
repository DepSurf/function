# Function: <code>count_strings</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd7a6)
Location: drivers/xen/xenbus/xenbus_xs.c:344
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:split
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e326)
Location: drivers/xen/xenbus/xenbus_xs.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:split
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a7a6)
Location: drivers/xen/xenbus/xenbus_xs.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:split
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155e4e0)
Location: drivers/xen/xenbus/xenbus_xs.c:365
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8155e4e0-ffffffff8155e524: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c2800)
Location: drivers/xen/xenbus/xenbus_xs.c:368
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff815c2800-ffffffff815c2844: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fae40)
Location: drivers/xen/xenbus/xenbus_xs.c:370
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff815fae40-ffffffff815fae8c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81615ef0)
Location: drivers/xen/xenbus/xenbus_xs.c:370
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81615ef0-ffffffff81615f3c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81649b50)
Location: drivers/xen/xenbus/xenbus_xs.c:373
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81649b50-ffffffff81649b9c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166bff0)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8166bff0-ffffffff8166c03c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c000)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff8171c000-ffffffff8171c04c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81738fb0)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff81738fb0-ffffffff81738ffc: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c9d0)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff8171c9d0-ffffffff8171ca1c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179b740)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff8179b740-ffffffff8179b78c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d4ca0)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff818d4ca0-ffffffff818d4cfc: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a26fe0)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff81a26fe0-ffffffff81a2702c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a70650)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff81a70650-ffffffff81a7069c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac2750)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:split
```
**Symbols:**

```
ffffffff81ac2750-ffffffff81ac279c: count_strings (STB_LOCAL)
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
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff8000108363e0)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffff8000108363e0-ffff800010836440: count_strings (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81631e60)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81631e60-ffffffff81631eac: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8165fe30)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8165fe30-ffffffff8165fe7c: count_strings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int count_strings(const char *strings, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167a480)
Location: drivers/xen/xenbus/xenbus_xs.c:376
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8167a480-ffffffff8167a4cc: count_strings (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
