# Function: <code>memory_read_from_io_buffer</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130bd60)
Location: fs/libfs.c:749
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
```
**Symbols:**

```
ffffffff8130bd60-ffffffff8130bdb3: memory_read_from_io_buffer (STB_GLOBAL)
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
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c0370)
Location: fs/libfs.c:749
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
```
**Symbols:**

```
ffff8000103c0370-ffff8000103c03f8: memory_read_from_io_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d7a4)
Location: fs/libfs.c:749
Inline: False
```
**Symbols:**

```
c059d7a4-c059d83c: memory_read_from_io_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004bf920)
Location: fs/libfs.c:749
Inline: False
```
**Symbols:**

```
c0000000004bf920-c0000000004bfa34: memory_read_from_io_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (0)
Location: fs/libfs.c:749
Inline: False
```
**Symbols:**

```
ffffffe000280b7e-ffffffe000280bc6: memory_read_from_io_buffer (STB_GLOBAL)
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
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81304340)
Location: fs/libfs.c:749
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
```
**Symbols:**

```
ffffffff81304340-ffffffff81304393: memory_read_from_io_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f4f60)
Location: fs/libfs.c:749
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
```
**Symbols:**

```
ffffffff812f4f60-ffffffff812f4fb3: memory_read_from_io_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81302130)
Location: fs/libfs.c:749
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
```
**Symbols:**

```
ffffffff81302130-ffffffff81302183: memory_read_from_io_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t memory_read_from_io_buffer(void *to, size_t count, loff_t *ppos, const void *from, size_t available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313750)
Location: fs/libfs.c:749
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_data_show
```
**Symbols:**

```
ffffffff81313750-ffffffff813137a3: memory_read_from_io_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
