# Function: <code>spi_mem_exec_op</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81733f40)
Location: drivers/spi/spi-mem.c:190
Inline: False
```
**Symbols:**

```
ffffffff81733f40-ffffffff817343d8: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81756d40)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffff81756d40-ffffffff8175715d: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81793390)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff81793390-ffffffff817937cf: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817b6ee0)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff817b6ee0-ffffffff817b731f: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8187dd30)
Location: drivers/spi/spi-mem.c:275
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff8187dd30-ffffffff8187e1ca: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8188c2b0)
Location: drivers/spi/spi-mem.c:282
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff8188c2b0-ffffffff8188c73c: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8186ee70)
Location: drivers/spi/spi-mem.c:298
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffff8186ee70-ffffffff8186f332: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:299
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffff81d10131-ffffffff81d10155: spi_mem_exec_op.cold (STB_LOCAL)
ffffffff818fef80-ffffffff818ff6ab: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:312
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffff81edae6e-ffffffff81edae92: spi_mem_exec_op.cold (STB_LOCAL)
ffffffff81a50540-ffffffff81a50c5a: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:312
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffff8209d485-ffffffff8209d4a9: spi_mem_exec_op.cold (STB_LOCAL)
ffffffff81bd96e0-ffffffff81bd9e12: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:312
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffff8211e342-ffffffff8211e37a: spi_mem_exec_op.cold (STB_LOCAL)
ffffffff81c300e0-ffffffff81c30898: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:312
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffff821ff8d0-ffffffff821ff8fe: spi_mem_exec_op.cold (STB_LOCAL)
ffffffff81ce2fa0-ffffffff81ce36f5: spi_mem_exec_op (STB_GLOBAL)
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
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffff8000109cad00)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffff8000109cad00-ffff8000109cb080: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c0ab40a4)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
c0ab40a4-c0ab43ec: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c000000000a8c5e0)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
c000000000a8c5e0-c000000000a8ca0c: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffe00061a5d4)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_no_dirmap_read
```
**Symbols:**

```
ffffffe00061a5d4-ffffffe00061a912: spi_mem_exec_op (STB_GLOBAL)
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
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8177b9c0)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff8177b9c0-ffffffff8177bdff: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8175b770)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff8175b770-ffffffff8175bbaf: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817abd60)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff817abd60-ffffffff817ac19f: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c5cf0)
Location: drivers/spi/spi-mem.c:273
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
```
**Symbols:**

```
ffffffff817c5cf0-ffffffff817c612f: spi_mem_exec_op (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
