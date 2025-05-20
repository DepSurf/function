# Function: <code>mmc_spi_send_cxd</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_spi_send_cxd(struct mmc_host *host, u32 *cxd, u32 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81995380)
Location: drivers/mmc/core/mmc_ops.c:299
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81995380-ffffffff81995405: mmc_spi_send_cxd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_spi_send_cxd(struct mmc_host *host, u32 *cxd, u32 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a41610)
Location: drivers/mmc/core/mmc_ops.c:303
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81a41610-ffffffff81a41697: mmc_spi_send_cxd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_spi_send_cxd(struct mmc_host *host, u32 *cxd, u32 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81baebf0)
Location: drivers/mmc/core/mmc_ops.c:332
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81baebf0-ffffffff81baec89: mmc_spi_send_cxd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_spi_send_cxd(struct mmc_host *host, u32 *cxd, u32 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d52520)
Location: drivers/mmc/core/mmc_ops.c:332
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81d52520-ffffffff81d525b9: mmc_spi_send_cxd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_spi_send_cxd(struct mmc_host *host, u32 *cxd, u32 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbcf30)
Location: drivers/mmc/core/mmc_ops.c:332
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81dbcf30-ffffffff81dbcfc9: mmc_spi_send_cxd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_spi_send_cxd(struct mmc_host *host, u32 *cxd, u32 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75500)
Location: drivers/mmc/core/mmc_ops.c:332
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_cid
  - drivers/mmc/core/mmc_ops.c:mmc_send_csd
```
**Symbols:**

```
ffffffff81e75500-ffffffff81e755c8: mmc_spi_send_cxd (STB_LOCAL)
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
