# Function: <code>tegra_fuse_read_early</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 tegra_fuse_read_early(unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/tegra/fuse/fuse-tegra.c (c1591e64)
Location: drivers/soc/tegra/fuse/fuse-tegra.c:182
Inline: False
Direct callers:
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_revision
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_init
  - drivers/soc/tegra/fuse/speedo-tegra30.c:tegra30_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra30.c:tegra30_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra30.c:tegra30_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra114.c:tegra114_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra114.c:tegra114_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra114.c:tegra114_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra114.c:tegra114_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra124.c:tegra124_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra124.c:tegra124_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra124.c:tegra124_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra124.c:tegra124_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra124.c:tegra124_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra124.c:tegra124_init_speedo_data
  - drivers/soc/tegra/fuse/speedo-tegra124.c:tegra124_init_speedo_data
```
**Symbols:**

```
c1591e64-c1591e94: tegra_fuse_read_early (STB_GLOBAL)
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
