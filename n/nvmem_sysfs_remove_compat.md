# Function: <code>nvmem_sysfs_remove_compat</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffff818d21e0)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffff818d21e0-ffffffff818d2205: nvmem_sysfs_remove_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffff81904590)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffff81904590-ffffffff819045b5: nvmem_sysfs_remove_compat (STB_GLOBAL)
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
In drivers/nvmem/core.c (ffffffff819db44b)
Location: drivers/nvmem/core.c:293
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
In drivers/nvmem/core.c (ffffffff819daacd)
Location: drivers/nvmem/core.c:383
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
In drivers/nvmem/core.c (ffffffff819c069d)
Location: drivers/nvmem/core.c:383
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
In drivers/nvmem/core.c (ffffffff81d346ce)
Location: drivers/nvmem/core.c:389
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
In drivers/nvmem/core.c (ffffffff81f00b15)
Location: drivers/nvmem/core.c:394
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
In drivers/nvmem/core.c (ffffffff820aa981)
Location: drivers/nvmem/core.c:394
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
In drivers/nvmem/core.c (ffffffff8212be7e)
Location: drivers/nvmem/core.c:402
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
In drivers/nvmem/core.c (ffffffff8220db33)
Location: drivers/nvmem/core.c:423
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
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffff800010ba0800)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffff800010ba0800-ffff800010ba0848: nvmem_sysfs_remove_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (c0c8238c)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
c0c8238c-c0c823bc: nvmem_sysfs_remove_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (c000000000c748b0)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
c000000000c748b0-c000000000c748fc: nvmem_sysfs_remove_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffe0007387ac)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffe0007387ac-ffffffe0007387f4: nvmem_sysfs_remove_compat (STB_GLOBAL)
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
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffff818a39c0)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffff818a39c0-ffffffff818a39e5: nvmem_sysfs_remove_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffff8185f130)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffff8185f130-ffffffff8185f155: nvmem_sysfs_remove_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffff818f4fb0)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffff818f4fb0-ffffffff818f4fd5: nvmem_sysfs_remove_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvmem_sysfs_remove_compat(struct nvmem_device *nvmem, const struct nvmem_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/nvmem-sysfs.c (ffffffff81916050)
Location: drivers/nvmem/nvmem-sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffff81916050-ffffffff81916075: nvmem_sysfs_remove_compat (STB_GLOBAL)
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
