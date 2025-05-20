# Function: <code>nvmem_sysfs_setup_compat</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (0)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffff818d2205-ffffffff818d2221: nvmem_sysfs_setup_compat.cold (STB_LOCAL)
ffffffff818d1fa0-ffffffff818d21dc: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (0)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffff819045b5-ffffffff819045d1: nvmem_sysfs_setup_compat.cold (STB_LOCAL)
ffffffff81904350-ffffffff8190458c: nvmem_sysfs_setup_compat (STB_GLOBAL)
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
In drivers/nvmem/core.c (ffffffff819db34c)
Location: drivers/nvmem/core.c:261
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff819da98f)
Location: drivers/nvmem/core.c:351
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff819c0560)
Location: drivers/nvmem/core.c:351
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff81d3472e)
Location: drivers/nvmem/core.c:354
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff81f00a94)
Location: drivers/nvmem/core.c:359
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff820aa90f)
Location: drivers/nvmem/core.c:359
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff8212be36)
Location: drivers/nvmem/core.c:367
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff8220dba4)
Location: drivers/nvmem/core.c:388
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffff800010ba0680)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffff800010ba0680-ffff800010ba07fc: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (c0c82298)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
c0c82298-c0c8238c: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (c000000000c74690)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
c000000000c74690-c000000000c748b0: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffe000738680)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffe000738680-ffffffe0007387ac: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (0)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffff818a39e5-ffffffff818a3a01: nvmem_sysfs_setup_compat.cold (STB_LOCAL)
ffffffff818a3780-ffffffff818a39bc: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (0)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffff8185f155-ffffffff8185f171: nvmem_sysfs_setup_compat.cold (STB_LOCAL)
ffffffff8185eef0-ffffffff8185f12c: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (0)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffff818f4fd5-ffffffff818f4ff1: nvmem_sysfs_setup_compat.cold (STB_LOCAL)
ffffffff818f4d70-ffffffff818f4fac: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvmem_sysfs_setup_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (0)
Location: drivers/nvmem/nvmem-sysfs.c:216
Inline: False
```
**Symbols:**

```
ffffffff81916075-ffffffff81916091: nvmem_sysfs_setup_compat.cold (STB_LOCAL)
ffffffff81915e10-ffffffff8191604c: nvmem_sysfs_setup_compat (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
