# Function: <code>ext4_kvzalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7ae0)
Location: fs/ext4/super.c:165
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
**Symbols:**

```
ffffffff812b7ae0-ffffffff812b7b22: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e67e0)
Location: fs/ext4/super.c:194
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
**Symbols:**

```
ffffffff812e67e0-ffffffff812e6822: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fc390)
Location: fs/ext4/super.c:196
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
**Symbols:**

```
ffffffff812fc390-ffffffff812fc3d2: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81330fe0)
Location: fs/ext4/super.c:198
Inline: False
```
**Symbols:**

```
ffffffff81330fe0-ffffffff81331022: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813554a0)
Location: fs/ext4/super.c:198
Inline: False
```
**Symbols:**

```
ffffffff813554a0-ffffffff813554e9: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813838d0)
Location: fs/ext4/super.c:198
Inline: False
```
**Symbols:**

```
ffffffff813838d0-ffffffff81383920: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139c3b0)
Location: fs/ext4/super.c:221
Inline: False
```
**Symbols:**

```
ffffffff8139c3b0-ffffffff8139c400: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c6600)
Location: fs/ext4/super.c:222
Inline: False
```
**Symbols:**

```
ffffffff813c6600-ffffffff813c6650: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813df9c0)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
ffffffff813df9c0-ffffffff813dfa10: ext4_kvzalloc (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b8748)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
ffff8000104b8748-ffff8000104b8838: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067bfdc)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
c067bfdc-c067c028: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ed980)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
c0000000005ed980-c0000000005eda18: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335202)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
ffffffe000335202-ffffffe00033525c: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d7fa0)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
ffffffff813d7fa0-ffffffff813d7ff0: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8a20)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
ffffffff813c8a20-ffffffff813c8a70: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d5430)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
ffffffff813d5430-ffffffff813d5480: ext4_kvzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ext4_kvzalloc(size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ea6b0)
Location: fs/ext4/super.c:217
Inline: False
```
**Symbols:**

```
ffffffff813ea6b0-ffffffff813ea700: ext4_kvzalloc (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
