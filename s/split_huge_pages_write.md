# Function: <code>split_huge_pages_write</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t split_huge_pages_write(struct file *file, const char *buf, size_t count, loff_t *ppops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff81300ac0)
Location: mm/huge_memory.c:3121
Inline: True
```
**Symbols:**

```
ffffffff81300880-ffffffff81300ab3: split_huge_pages_write.part.0 (STB_LOCAL)
ffffffff81bdbb61-ffffffff81bdbb79: split_huge_pages_write.part.0.cold (STB_LOCAL)
ffffffff81300ac0-ffffffff81300af7: split_huge_pages_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t split_huge_pages_write(struct file *file, const char *buf, size_t count, loff_t *ppops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff8134a760)
Location: mm/huge_memory.c:3064
Inline: True
```
**Symbols:**

```
ffffffff8134a510-ffffffff8134a75a: split_huge_pages_write.part.0 (STB_LOCAL)
ffffffff81cc261a-ffffffff81cc263e: split_huge_pages_write.part.0.cold (STB_LOCAL)
ffffffff8134a760-ffffffff8134a797: split_huge_pages_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t split_huge_pages_write(struct file *file, const char *buf, size_t count, loff_t *ppops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:3032
Inline: False
```
**Symbols:**

```
ffffffff813c11f0-ffffffff813c14e9: split_huge_pages_write (STB_LOCAL)
ffffffff81e74be8-ffffffff81e74c0c: split_huge_pages_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t split_huge_pages_write(struct file *file, const char *buf, size_t count, loff_t *ppops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81443270)
Location: mm/huge_memory.c:3130
Inline: False
```
**Symbols:**

```
ffffffff81443270-ffffffff81443584: split_huge_pages_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t split_huge_pages_write(struct file *file, const char *buf, size_t count, loff_t *ppops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814789a0)
Location: mm/huge_memory.c:3138
Inline: False
```
**Symbols:**

```
ffffffff814789a0-ffffffff81478cb4: split_huge_pages_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t split_huge_pages_write(struct file *file, const char *buf, size_t count, loff_t *ppops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a7f90)
Location: mm/huge_memory.c:3466
Inline: False
```
**Symbols:**

```
ffffffff814a7f90-ffffffff814a82a4: split_huge_pages_write (STB_LOCAL)
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
