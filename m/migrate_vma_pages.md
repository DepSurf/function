# Function: <code>migrate_vma_pages</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124c684)
Location: mm/migrate.c:2748
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
In mm/migrate.c (ffffffff812701cf)
Location: mm/migrate.c:2761
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
In mm/migrate.c (ffffffff81284894)
Location: mm/migrate.c:2740
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812af580)
Location: mm/migrate.c:2842
Inline: False
```
**Symbols:**

```
ffffffff812af580-ffffffff812af769: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e5610)
Location: mm/migrate.c:2864
Inline: False
```
**Symbols:**

```
ffffffff812e5610-ffffffff812e57fc: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f09e0)
Location: mm/migrate.c:3033
Inline: False
```
**Symbols:**

```
ffffffff812f09e0-ffffffff812f0bd1: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f6d30)
Location: mm/migrate.c:3003
Inline: False
```
**Symbols:**

```
ffffffff812f6d30-ffffffff812f6f23: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81341390)
Location: mm/migrate.c:2940
Inline: False
```
**Symbols:**

```
ffffffff81341390-ffffffff81341583: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff813b82c0)
Location: mm/migrate_device.c:666
Inline: False
```
**Symbols:**

```
ffffffff813b82c0-ffffffff813b84d7: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff8143a3a0)
Location: mm/migrate_device.c:810
Inline: False
```
**Symbols:**

```
ffffffff8143a3a0-ffffffff8143a3cb: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff8146eff0)
Location: mm/migrate_device.c:791
Inline: False
```
**Symbols:**

```
ffffffff8146eff0-ffffffff8146f01b: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff8149daf0)
Location: mm/migrate_device.c:799
Inline: False
```
**Symbols:**

```
ffffffff8149daf0-ffffffff8149db1b: migrate_vma_pages (STB_GLOBAL)
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
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004338f0)
Location: mm/migrate.c:2842
Inline: False
```
**Symbols:**

```
c0000000004338f0-c000000000433bcc: migrate_vma_pages (STB_GLOBAL)
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
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7b60)
Location: mm/migrate.c:2842
Inline: False
```
**Symbols:**

```
ffffffff812a7b60-ffffffff812a7d49: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81299520)
Location: mm/migrate.c:2842
Inline: False
```
**Symbols:**

```
ffffffff81299520-ffffffff81299709: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5970)
Location: mm/migrate.c:2842
Inline: False
```
**Symbols:**

```
ffffffff812a5970-ffffffff812a5b59: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void migrate_vma_pages(struct migrate_vma *migrate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b50a0)
Location: mm/migrate.c:2842
Inline: False
```
**Symbols:**

```
ffffffff812b50a0-ffffffff812b5291: migrate_vma_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
