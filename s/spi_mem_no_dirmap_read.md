# Function: <code>spi_mem_no_dirmap_read</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817572f0)
Location: drivers/spi/spi-mem.c:442
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff817572f0-ffffffff81757389: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81793a4a)
Location: drivers/spi/spi-mem.c:442
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
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
In drivers/spi/spi-mem.c (ffffffff817b759a)
Location: drivers/spi/spi-mem.c:442
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
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
In drivers/spi/spi-mem.c (ffffffff8187e2cf)
Location: drivers/spi/spi-mem.c:445
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
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
In drivers/spi/spi-mem.c (ffffffff8188c83f)
Location: drivers/spi/spi-mem.c:450
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8186f340)
Location: drivers/spi/spi-mem.c:467
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff8186f340-ffffffff8186f3db: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff818ff6b0)
Location: drivers/spi/spi-mem.c:468
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff818ff6b0-ffffffff818ff74b: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81a512d0)
Location: drivers/spi/spi-mem.c:481
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff81a512d0-ffffffff81a51372: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81bda4f0)
Location: drivers/spi/spi-mem.c:481
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff81bda4f0-ffffffff81bda592: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81c30f90)
Location: drivers/spi/spi-mem.c:481
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff81c30f90-ffffffff81c31032: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81ce3e20)
Location: drivers/spi/spi-mem.c:481
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff81ce3e20-ffffffff81ce3ec2: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffff8000109cb1e0)
Location: drivers/spi/spi-mem.c:442
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffff8000109cb1e0-ffff8000109cb2a8: spi_mem_no_dirmap_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c0ab4544)
Location: drivers/spi/spi-mem.c:442
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
c0ab4544-c0ab4610: spi_mem_no_dirmap_read (STB_LOCAL)
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
In drivers/spi/spi-mem.c (c000000000a8cd80)
Location: drivers/spi/spi-mem.c:442
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_read(struct spi_mem_dirmap_desc *desc, u64 offs, size_t len, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffe00061aa0c)
Location: drivers/spi/spi-mem.c:442
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffe00061aa0c-ffffffe00061aaa2: spi_mem_no_dirmap_read (STB_LOCAL)
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
In drivers/spi/spi-mem.c (ffffffff8177c07a)
Location: drivers/spi/spi-mem.c:442
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
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
In drivers/spi/spi-mem.c (ffffffff8175be2a)
Location: drivers/spi/spi-mem.c:442
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817ac41a)
Location: drivers/spi/spi-mem.c:442
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c63aa)
Location: drivers/spi/spi-mem.c:442
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
</details>
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
<b>Arch</b>
<ul>
</ul>
