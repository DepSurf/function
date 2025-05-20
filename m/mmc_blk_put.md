# Function: <code>mmc_blk_put</code>

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
void mmc_blk_put(struct mmc_blk_data *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b3f600)
Location: drivers/mmc/core/block.c:193
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_release
  - drivers/mmc/core/block.c:mmc_blk_release
  - drivers/mmc/core/block.c:mmc_blk_open
  - drivers/mmc/core/block.c:force_ro_store
  - drivers/mmc/core/block.c:force_ro_show
  - drivers/mmc/core/block.c:power_ro_lock_show
```
**Symbols:**

```
ffff800010b3f600-ffff800010b3f69c: mmc_blk_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_blk_put(struct mmc_blk_data *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (c0c19d48)
Location: drivers/mmc/core/block.c:193
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_release
  - drivers/mmc/core/block.c:mmc_blk_release
  - drivers/mmc/core/block.c:mmc_blk_open
  - drivers/mmc/core/block.c:force_ro_store
  - drivers/mmc/core/block.c:force_ro_show
  - drivers/mmc/core/block.c:power_ro_lock_show
```
**Symbols:**

```
c0c19d48-c0c19dd0: mmc_blk_put (STB_LOCAL)
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
void mmc_blk_put(struct mmc_blk_data *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe000716424)
Location: drivers/mmc/core/block.c:193
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_release
  - drivers/mmc/core/block.c:mmc_blk_release
  - drivers/mmc/core/block.c:mmc_blk_open
  - drivers/mmc/core/block.c:force_ro_store
  - drivers/mmc/core/block.c:force_ro_show
  - drivers/mmc/core/block.c:power_ro_lock_show
```
**Symbols:**

```
ffffffe000716424-ffffffe0007164bc: mmc_blk_put (STB_LOCAL)
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
