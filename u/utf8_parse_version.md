# Function: <code>utf8_parse_version</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int utf8_parse_version(const char *version, unsigned int *maj, unsigned int *min, unsigned int *rev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81404fa0)
Location: fs/unicode/utf8-core.c:152
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_load
```
**Symbols:**

```
ffffffff81404fa0-ffffffff81405075: utf8_parse_version (STB_LOCAL)
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
In fs/unicode/utf8-core.c (ffffffff8141ef7e)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (ffffffff8146db99)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (ffffffff81488349)
Location: fs/unicode/utf8-core.c:173
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (ffffffff8148dd2e)
Location: fs/unicode/utf8-core.c:173
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (ffffffff814e579e)
Location: fs/unicode/utf8-core.c:173
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffff8000105011dc)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (c06bde90)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (c000000000645510)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (ffffffe00036e850)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (ffffffff8141755e)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
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
In fs/unicode/utf8-core.c (ffffffff81407fde)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8142a53e)
Location: fs/unicode/utf8-core.c:152
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
