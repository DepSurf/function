# Function: <code>spi_mem_default_supports_op</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81733de0)
Location: drivers/spi/spi-mem.c:129
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff81733de0-ffffffff81733e75: spi_mem_default_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817569b0)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffff817569b0-ffffffff81756a44: spi_mem_default_supports_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81792f70)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffff81792f70-ffffffff81793006: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817b6ac0)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffff817b6ac0-ffffffff817b6b56: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8187dc60)
Location: drivers/spi/spi-mem.c:140
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff8187dc60-ffffffff8187dd27: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8188c1c0)
Location: drivers/spi/spi-mem.c:140
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff8188c1c0-ffffffff8188c2ab: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8186f1da)
Location: drivers/spi/spi-mem.c:172
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff8186ec10-ffffffff8186ec40: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff818ff3a1)
Location: drivers/spi/spi-mem.c:173
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_exec_op
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff818fed20-ffffffff818fed50: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:164
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff81edae44-ffffffff81edae6e: spi_mem_default_supports_op.cold (STB_LOCAL)
ffffffff81a50400-ffffffff81a50539: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:164
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff8209d45b-ffffffff8209d485: spi_mem_default_supports_op.cold (STB_LOCAL)
ffffffff81bd9590-ffffffff81bd96c9: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:164
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff8211e318-ffffffff8211e342: spi_mem_default_supports_op.cold (STB_LOCAL)
ffffffff81c2ff90-ffffffff81c300c9: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (0)
Location: drivers/spi/spi-mem.c:164
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/spi/spi-mem.c:spi_mem_supports_op
```
**Symbols:**

```
ffffffff821ff8a6-ffffffff821ff8d0: spi_mem_default_supports_op.cold (STB_LOCAL)
ffffffff81ce2e50-ffffffff81ce2f89: spi_mem_default_supports_op (STB_GLOBAL)
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
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffff8000109ca858)
Location: drivers/spi/spi-mem.c:138
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffff8000109ca858-ffff8000109ca90c: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c0ab3d40)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
c0ab3d40-c0ab3df8: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c000000000a8c1a0)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
c000000000a8c1a0-c000000000a8c2d0: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffe00061a1e8)
Location: drivers/spi/spi-mem.c:138
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffe00061a1e8-ffffffe00061a28a: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8177b5a0)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffff8177b5a0-ffffffff8177b636: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8175b350)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffff8175b350-ffffffff8175b3e6: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817ab940)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffff817ab940-ffffffff817ab9d6: spi_mem_default_supports_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem *mem, const struct spi_mem_op *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c58d0)
Location: drivers/spi/spi-mem.c:138
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_internal_supports_op
```
**Symbols:**

```
ffffffff817c58d0-ffffffff817c5966: spi_mem_default_supports_op (STB_GLOBAL)
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
