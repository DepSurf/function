# Function: <code>devmap_managed_enable_put</code>

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
void devmap_managed_enable_put(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c22e0)
Location: mm/memremap.c:24
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812c22e0-ffffffff812c2301: devmap_managed_enable_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devmap_managed_enable_put();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4250)
Location: mm/memremap.c:22
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812d4250-ffffffff812d4271: devmap_managed_enable_put (STB_LOCAL)
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
In mm/memremap.c (ffffffff8130a232)
Location: mm/memremap.c:45
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff81316481)
Location: mm/memremap.c:44
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff8131c6ba)
Location: mm/memremap.c:44
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff813699b3)
Location: mm/memremap.c:44
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff813e733b)
Location: mm/memremap.c:45
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff8146efa6)
Location: mm/memremap.c:45
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff814a3782)
Location: mm/memremap.c:45
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In mm/memremap.c (ffffffff814d4622)
Location: mm/memremap.c:46
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devmap_managed_enable_put();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046d770)
Location: mm/memremap.c:22
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
c00000000046d770-c00000000046d7d8: devmap_managed_enable_put (STB_LOCAL)
```
</details>
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
void devmap_managed_enable_put();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cc830)
Location: mm/memremap.c:22
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812cc830-ffffffff812cc851: devmap_managed_enable_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devmap_managed_enable_put();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812bd6a0)
Location: mm/memremap.c:22
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812bd6a0-ffffffff812bd6c1: devmap_managed_enable_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devmap_managed_enable_put();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812ca640)
Location: mm/memremap.c:22
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812ca640-ffffffff812ca661: devmap_managed_enable_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devmap_managed_enable_put();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812db340)
Location: mm/memremap.c:22
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812db340-ffffffff812db361: devmap_managed_enable_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
