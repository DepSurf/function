# Function: <code>utf8hangul</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81404049)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff8141dff9)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
utf8leaf_t *utf8hangul(const char *str, unsigned char *hangul);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8146cb10)
Location: fs/unicode/utf8-norm.c:275
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
```
**Symbols:**

```
ffffffff8146cb10-ffffffff8146cc0a: utf8hangul (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
utf8leaf_t *utf8hangul(const char *str, unsigned char *hangul);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814871f0)
Location: fs/unicode/utf8-norm.c:275
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
```
**Symbols:**

```
ffffffff814871f0-ffffffff814872ea: utf8hangul (STB_LOCAL)
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
In fs/unicode/utf8-norm.c (ffffffff8148cced)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff814e456d)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff81572a06)
Location: fs/unicode/utf8-norm.c:258
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff81617f66)
Location: fs/unicode/utf8-norm.c:258
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff81650036)
Location: fs/unicode/utf8-norm.c:258
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff81689616)
Location: fs/unicode/utf8-norm.c:258
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffff8000104fffe4)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (c06bcd98)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (c000000000643cfc)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffe00036daa2)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff814165d9)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff81407059)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
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
In fs/unicode/utf8-norm.c (ffffffff814295b9)
Location: fs/unicode/utf8-norm.c:275
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8nlookup
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
