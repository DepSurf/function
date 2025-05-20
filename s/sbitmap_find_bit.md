# Function: <code>sbitmap_find_bit</code>

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
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sbitmap_find_bit(struct sbitmap *sb, unsigned int depth, unsigned int index, unsigned int alloc_hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:189
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff818e5c00-ffffffff818e5d89: sbitmap_find_bit (STB_LOCAL)
ffffffff8210dc0f-ffffffff8210dc92: sbitmap_find_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sbitmap_find_bit(struct sbitmap *sb, unsigned int depth, unsigned int index, unsigned int alloc_hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:189
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff8192cc00-ffffffff8192cd89: sbitmap_find_bit (STB_LOCAL)
ffffffff821eb84c-ffffffff821eb8cf: sbitmap_find_bit.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
