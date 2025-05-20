# Function: <code>spi_mem_internal_supports_op</code>

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
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81756a50)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff81756a50-ffffffff81756a86: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81793010)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff81793010-ffffffff81793046: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817b6b60)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff817b6b60-ffffffff817b6b96: spi_mem_internal_supports_op (STB_LOCAL)
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
In drivers/spi/spi-mem.c (ffffffff8187ddb1)
Location: drivers/spi/spi-mem.c:190
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
In drivers/spi/spi-mem.c (ffffffff8188c331)
Location: drivers/spi/spi-mem.c:196
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
In drivers/spi/spi-mem.c (ffffffff8186eef8)
Location: drivers/spi/spi-mem.c:212
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
In drivers/spi/spi-mem.c (ffffffff818ff008)
Location: drivers/spi/spi-mem.c:213
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
In drivers/spi/spi-mem.c (ffffffff81a505e7)
Location: drivers/spi/spi-mem.c:227
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
In drivers/spi/spi-mem.c (ffffffff81bd978a)
Location: drivers/spi/spi-mem.c:227
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
In drivers/spi/spi-mem.c (ffffffff81c3018d)
Location: drivers/spi/spi-mem.c:227
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
In drivers/spi/spi-mem.c (ffffffff81ce304d)
Location: drivers/spi/spi-mem.c:227
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
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
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffff8000109ca910)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffff8000109ca910-ffff8000109ca978: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c0ab3df8)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
c0ab3df8-c0ab3e4c: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c000000000a8c2d0)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
c000000000a8c2d0-c000000000a8c34c: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffe00061a28a)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffe00061a28a-ffffffe00061a2da: spi_mem_internal_supports_op (STB_LOCAL)
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
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8177b640)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff8177b640-ffffffff8177b676: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8175b3f0)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff8175b3f0-ffffffff8175b426: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817ab9e0)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff817ab9e0-ffffffff817aba16: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool spi_mem_internal_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c5970)
Location: drivers/spi/spi-mem.c:188
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff817c5970-ffffffff817c59a6: spi_mem_internal_supports_op (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
