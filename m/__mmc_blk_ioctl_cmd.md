# Function: <code>__mmc_blk_ioctl_cmd</code>

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
int __mmc_blk_ioctl_cmd(struct mmc_card *card, struct mmc_blk_data *md, struct mmc_blk_ioc_data *idata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b41a78)
Location: drivers/mmc/core/block.c:491
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffff800010b41a78-ffff800010b41f8c: __mmc_blk_ioctl_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mmc_blk_ioctl_cmd(struct mmc_card *card, struct mmc_blk_data *md, struct mmc_blk_ioc_data *idata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (c0c1c664)
Location: drivers/mmc/core/block.c:491
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
c0c1c664-c0c1cb94: __mmc_blk_ioctl_cmd (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mmc_blk_ioctl_cmd(struct mmc_card *card, struct mmc_blk_data *md, struct mmc_blk_ioc_data *idata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe00071873c)
Location: drivers/mmc/core/block.c:491
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffffffe00071873c-ffffffe000718c04: __mmc_blk_ioctl_cmd (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
