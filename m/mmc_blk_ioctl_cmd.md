# Function: <code>mmc_blk_ioctl_cmd</code>

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
int mmc_blk_ioctl_cmd(struct mmc_blk_data *md, struct mmc_ioc_cmd *ic_ptr, struct mmc_rpmb_data *rpmb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b428b8)
Location: drivers/mmc/core/block.c:644
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_rpmb_ioctl
```
**Symbols:**

```
ffff800010b428b8-ffff800010b42a1c: mmc_blk_ioctl_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_blk_ioctl_cmd(struct mmc_blk_data *md, struct mmc_ioc_cmd *ic_ptr, struct mmc_rpmb_data *rpmb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (c0c1b614)
Location: drivers/mmc/core/block.c:644
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_rpmb_ioctl
```
**Symbols:**

```
c0c1b614-c0c1b744: mmc_blk_ioctl_cmd (STB_LOCAL)
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
int mmc_blk_ioctl_cmd(struct mmc_blk_data *md, struct mmc_ioc_cmd *ic_ptr, struct mmc_rpmb_data *rpmb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe000716b8e)
Location: drivers/mmc/core/block.c:644
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_rpmb_ioctl
```
**Symbols:**

```
ffffffe000716b8e-ffffffe000716c84: mmc_blk_ioctl_cmd (STB_LOCAL)
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
