# Function: <code>scsi_init_hctx</code>

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
int scsi_init_hctx(struct blk_mq_hw_ctx *hctx, void *data, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81827e70)
Location: drivers/scsi/scsi_lib.c:1793
Inline: False
```
**Symbols:**

```
ffffffff81827e70-ffffffff81827e84: scsi_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_init_hctx(struct blk_mq_hw_ctx *hctx, void *data, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b37d0)
Location: drivers/scsi/scsi_lib.c:1795
Inline: False
```
**Symbols:**

```
ffffffff818b37d0-ffffffff818b37e4: scsi_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_init_hctx(struct blk_mq_hw_ctx *hctx, void *data, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819fe990)
Location: drivers/scsi/scsi_lib.c:1852
Inline: False
```
**Symbols:**

```
ffffffff819fe990-ffffffff819fe9ac: scsi_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_init_hctx(struct blk_mq_hw_ctx *hctx, void *data, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7cf50)
Location: drivers/scsi/scsi_lib.c:1857
Inline: False
```
**Symbols:**

```
ffffffff81b7cf50-ffffffff81b7cf6c: scsi_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_init_hctx(struct blk_mq_hw_ctx *hctx, void *data, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd0cd0)
Location: drivers/scsi/scsi_lib.c:1861
Inline: False
```
**Symbols:**

```
ffffffff81bd0cd0-ffffffff81bd0cec: scsi_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_init_hctx(struct blk_mq_hw_ctx *hctx, void *data, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c25940)
Location: drivers/scsi/scsi_lib.c:1858
Inline: False
```
**Symbols:**

```
ffffffff81c25940-ffffffff81c2595c: scsi_init_hctx (STB_LOCAL)
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
