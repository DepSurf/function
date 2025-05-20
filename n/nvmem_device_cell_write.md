# Function: <code>nvmem_device_cell_write</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5dd0)
Location: drivers/nvmem/core.c:1154
Inline: False
```
**Symbols:**

```
ffffffff817a5dd0-ffffffff817a5e34: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181cf60)
Location: drivers/nvmem/core.c:1193
Inline: False
```
**Symbols:**

```
ffffffff8181cf60-ffffffff8181cfc4: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81867030)
Location: drivers/nvmem/core.c:1273
Inline: False
```
**Symbols:**

```
ffffffff81867030-ffffffff81867094: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886ed0)
Location: drivers/nvmem/core.c:1409
Inline: False
```
**Symbols:**

```
ffffffff81886ed0-ffffffff81886f34: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d1cf0)
Location: drivers/nvmem/core.c:1201
Inline: False
```
**Symbols:**

```
ffffffff818d1cf0-ffffffff818d1d56: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819040f0)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
ffffffff819040f0-ffffffff81904156: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1457
Inline: False
```
**Symbols:**

```
ffffffff819db872-ffffffff819db890: nvmem_device_cell_write.cold (STB_LOCAL)
ffffffff819daee0-ffffffff819dafab: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1650
Inline: False
```
**Symbols:**

```
ffffffff81c301ff-ffffffff81c3022a: nvmem_device_cell_write.cold (STB_LOCAL)
ffffffff819da4f0-ffffffff819da58f: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1748
Inline: False
```
**Symbols:**

```
ffffffff81c224f3-ffffffff81c2251e: nvmem_device_cell_write.cold (STB_LOCAL)
ffffffff819c0fc0-ffffffff819c1060: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1760
Inline: False
```
**Symbols:**

```
ffffffff81d347e1-ffffffff81d3480c: nvmem_device_cell_write.cold (STB_LOCAL)
ffffffff81a70800-ffffffff81a708a0: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1790
Inline: False
```
**Symbols:**

```
ffffffff81f00ba6-ffffffff81f00bce: nvmem_device_cell_write.cold (STB_LOCAL)
ffffffff81be17e0-ffffffff81be18b1: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d150)
Location: drivers/nvmem/core.c:1793
Inline: False
```
**Symbols:**

```
ffffffff81d8d150-ffffffff81d8d240: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfb750)
Location: drivers/nvmem/core.c:1975
Inline: False
```
**Symbols:**

```
ffffffff81dfb750-ffffffff81dfb869: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb2510)
Location: drivers/nvmem/core.c:2018
Inline: False
```
**Symbols:**

```
ffffffff81eb2510-ffffffff81eb2629: nvmem_device_cell_write (STB_GLOBAL)
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
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9fa50)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
ffff800010b9fa50-ffff800010b9fadc: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c82060)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
c0c82060-c0c820e4: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c74320)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
c000000000c74320-c000000000c743cc: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000737b86)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
ffffffe000737b86-ffffffe000737bdc: nvmem_device_cell_write (STB_GLOBAL)
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
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a3520)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
ffffffff818a3520-ffffffff818a3586: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185ec90)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
ffffffff8185ec90-ffffffff8185ecf6: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f4b10)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
ffffffff818f4b10-ffffffff818f4b76: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvmem_device_cell_write(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81915bb0)
Location: drivers/nvmem/core.c:1198
Inline: False
```
**Symbols:**

```
ffffffff81915bb0-ffffffff81915c16: nvmem_device_cell_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
