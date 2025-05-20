# Function: <code>__mtd_next_device</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct mtd_info *__mtd_next_device(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mtd/mtdcore.c (c0a8ff14)
Location: drivers/mtd/mtdcore.c:76
Inline: True
Inline callers:
  - drivers/mtd/mtdcore.c:mtd_proc_show
  - drivers/mtd/mtdcore.c:mtd_proc_show
  - drivers/mtd/mtdcore.c:get_mtd_device_nm
  - drivers/mtd/mtdcore.c:get_mtd_device_nm
  - drivers/mtd/mtdcore.c:get_mtd_device
  - drivers/mtd/mtdcore.c:get_mtd_device
  - drivers/mtd/mtdcore.c:unregister_mtd_user
  - drivers/mtd/mtdcore.c:unregister_mtd_user
  - drivers/mtd/mtdcore.c:register_mtd_user
  - drivers/mtd/mtdcore.c:register_mtd_user
Direct callers:
  - drivers/mtd/mtd_blkdevs.c:register_mtd_blktrans
  - drivers/mtd/mtd_blkdevs.c:register_mtd_blktrans
```
**Symbols:**

```
c0a8efc8-c0a8effc: __mtd_next_device (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
