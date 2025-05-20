# Function: <code>__sbitmap_get</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed617)
Location: lib/sbitmap.c:198
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:198
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff8165a620-ffffffff8165a74c: __sbitmap_get (STB_LOCAL)
ffffffff81cdef0c-ffffffff81cdef99: __sbitmap_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:188
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff81772d00-ffffffff81772e7e: __sbitmap_get (STB_LOCAL)
ffffffff81ea5322-ffffffff81ea53f0: __sbitmap_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __sbitmap_get(struct sbitmap *sb, unsigned int alloc_hint);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:188
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff818a3120-ffffffff818a329e: __sbitmap_get (STB_LOCAL)
ffffffff8208d726-ffffffff8208d7f4: __sbitmap_get.cold (STB_LOCAL)
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
In lib/sbitmap.c (ffffffff818e641f)
Location: lib/sbitmap.c:219
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get
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
In lib/sbitmap.c (ffffffff8192d43f)
Location: lib/sbitmap.c:219
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get
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
</ul>
