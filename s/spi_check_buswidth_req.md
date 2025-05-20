# Function: <code>spi_check_buswidth_req</code>

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
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81733b70)
Location: drivers/spi/spi-mem.c:100
Inline: False
```
**Symbols:**

```
ffffffff81733b70-ffffffff81733bee: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817565e0)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
ffffffff817565e0-ffffffff81756693: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81792b40)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
ffffffff81792b40-ffffffff81792bed: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817b6690)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
ffffffff817b6690-ffffffff817b673d: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8187d9c0)
Location: drivers/spi/spi-mem.c:102
Inline: True
```
**Symbols:**

```
ffffffff8187d9c0-ffffffff8187da6a: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8188bf20)
Location: drivers/spi/spi-mem.c:102
Inline: True
```
**Symbols:**

```
ffffffff8188bf20-ffffffff8188bfca: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8186e880)
Location: drivers/spi/spi-mem.c:102
Inline: True
```
**Symbols:**

```
ffffffff8186e880-ffffffff8186e92a: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff818fe990)
Location: drivers/spi/spi-mem.c:103
Inline: True
```
**Symbols:**

```
ffffffff818fe990-ffffffff818fea3a: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81a502f0)
Location: drivers/spi/spi-mem.c:104
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
**Symbols:**

```
ffffffff81a502f0-ffffffff81a503f6: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81bd9470)
Location: drivers/spi/spi-mem.c:104
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
**Symbols:**

```
ffffffff81bd9470-ffffffff81bd9576: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81c2fe70)
Location: drivers/spi/spi-mem.c:104
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
**Symbols:**

```
ffffffff81c2fe70-ffffffff81c2ff76: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81ce2d30)
Location: drivers/spi/spi-mem.c:104
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
**Symbols:**

```
ffffffff81ce2d30-ffffffff81ce2e36: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffff8000109ca740)
Location: drivers/spi/spi-mem.c:102
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
**Symbols:**

```
ffff8000109ca740-ffff8000109ca858: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c0ab3748)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
c0ab3748-c0ab3838: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (c000000000a8c0c0)
Location: drivers/spi/spi-mem.c:102
Inline: True
```
**Symbols:**

```
c000000000a8c0c0-c000000000a8c198: spi_check_buswidth_req.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffe00061a0fc)
Location: drivers/spi/spi-mem.c:102
Inline: True
Direct callers:
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
  - drivers/spi/spi-mem.c:spi_mem_default_supports_op
```
**Symbols:**

```
ffffffe00061a0fc-ffffffe00061a1e8: spi_check_buswidth_req.isra.0 (STB_LOCAL)
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
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8177b170)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
ffffffff8177b170-ffffffff8177b21d: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8175af20)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
ffffffff8175af20-ffffffff8175afcd: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817ab510)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
ffffffff817ab510-ffffffff817ab5bd: spi_check_buswidth_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int spi_check_buswidth_req(struct spi_mem *mem, u8 buswidth, bool tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c54a0)
Location: drivers/spi/spi-mem.c:102
Inline: False
```
**Symbols:**

```
ffffffff817c54a0-ffffffff817c554d: spi_check_buswidth_req (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
