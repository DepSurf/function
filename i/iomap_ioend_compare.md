# Function: <code>iomap_ioend_compare</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, struct list_head *a, struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813a9ce0)
Location: fs/iomap/buffered-io.c:1188
Inline: False
```
**Symbols:**

```
ffffffff813a9ce0-ffffffff813a9d01: iomap_ioend_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, struct list_head *a, struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bb330)
Location: fs/iomap/buffered-io.c:1158
Inline: False
```
**Symbols:**

```
ffffffff813bb330-ffffffff813bb351: iomap_ioend_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, const struct list_head *a, const struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c2450)
Location: fs/iomap/buffered-io.c:1154
Inline: False
```
**Symbols:**

```
ffffffff813c2450-ffffffff813c2471: iomap_ioend_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, const struct list_head *a, const struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81411f90)
Location: fs/iomap/buffered-io.c:1123
Inline: False
```
**Symbols:**

```
ffffffff81411f90-ffffffff81411fb1: iomap_ioend_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, const struct list_head *a, const struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81487ed0)
Location: fs/iomap/buffered-io.c:1150
Inline: False
```
**Symbols:**

```
ffffffff81487ed0-ffffffff81487ef9: iomap_ioend_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, const struct list_head *a, const struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151bb00)
Location: fs/iomap/buffered-io.c:1411
Inline: False
```
**Symbols:**

```
ffffffff8151bb00-ffffffff8151bb29: iomap_ioend_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, const struct list_head *a, const struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81553dc0)
Location: fs/iomap/buffered-io.c:1431
Inline: False
```
**Symbols:**

```
ffffffff81553dc0-ffffffff81553de9: iomap_ioend_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomap_ioend_compare(void *priv, const struct list_head *a, const struct list_head *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81589d80)
Location: fs/iomap/buffered-io.c:1599
Inline: False
```
**Symbols:**

```
ffffffff81589d80-ffffffff81589da9: iomap_ioend_compare (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct list_head *a</code> ➡️ <code>const struct list_head *a</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct list_head *b</code> ➡️ <code>const struct list_head *b</code>
</li>
</ul>
</details>
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
