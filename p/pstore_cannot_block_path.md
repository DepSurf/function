# Function: <code>pstore_cannot_block_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool pstore_cannot_block_path(enum kmsg_dump_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81320300)
Location: fs/pstore/platform.c:111
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81320300-ffffffff81320332: pstore_cannot_block_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool pstore_cannot_block_path(enum kmsg_dump_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81355a1a)
Location: fs/pstore/platform.c:132
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81355e00-ffffffff81355e32: pstore_cannot_block_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool pstore_cannot_block_path(enum kmsg_dump_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8136be4a)
Location: fs/pstore/platform.c:132
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8136c200-ffffffff8136c232: pstore_cannot_block_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool pstore_cannot_block_path(enum kmsg_dump_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81380729)
Location: fs/pstore/platform.c:132
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81380610-ffffffff81380642: pstore_cannot_block_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool pstore_cannot_block_path(enum kmsg_dump_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813a5739)
Location: fs/pstore/platform.c:132
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff813a5620-ffffffff813a5652: pstore_cannot_block_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool pstore_cannot_block_path(enum kmsg_dump_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813d4889)
Location: fs/pstore/platform.c:124
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff813d4590-ffffffff813d45ba: pstore_cannot_block_path (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81591b8e)
Location: fs/pstore/platform.c:146
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff816394be)
Location: fs/pstore/platform.c:148
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff816719a2)
Location: fs/pstore/platform.c:148
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff816ad872)
Location: fs/pstore/platform.c:150
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
</ul>
