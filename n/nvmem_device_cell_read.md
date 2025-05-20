# Function: <code>nvmem_device_cell_read</code>

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
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a57b0)
Location: drivers/nvmem/core.c:1123
Inline: False
```
**Symbols:**

```
ffffffff817a57b0-ffffffff817a582c: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181c920)
Location: drivers/nvmem/core.c:1162
Inline: False
```
**Symbols:**

```
ffffffff8181c920-ffffffff8181c99c: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81866a00)
Location: drivers/nvmem/core.c:1242
Inline: False
```
**Symbols:**

```
ffffffff81866a00-ffffffff81866a7c: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886880)
Location: drivers/nvmem/core.c:1378
Inline: False
```
**Symbols:**

```
ffffffff81886880-ffffffff818868fc: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0d50)
Location: drivers/nvmem/core.c:1170
Inline: False
```
**Symbols:**

```
ffffffff818d0d50-ffffffff818d0dd1: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903150)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
ffffffff81903150-ffffffff819031d1: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1426
Inline: False
```
**Symbols:**

```
ffffffff819db8a6-ffffffff819db8c6: nvmem_device_cell_read.cold (STB_LOCAL)
ffffffff819db500-ffffffff819db5df: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1619
Inline: False
```
**Symbols:**

```
ffffffff81c301d2-ffffffff81c301ff: nvmem_device_cell_read.cold (STB_LOCAL)
ffffffff819da1b0-ffffffff819da281: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1717
Inline: False
```
**Symbols:**

```
ffffffff81c224c6-ffffffff81c224f3: nvmem_device_cell_read.cold (STB_LOCAL)
ffffffff819c0c80-ffffffff819c0d5a: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1729
Inline: False
```
**Symbols:**

```
ffffffff81d3479f-ffffffff81d347cc: nvmem_device_cell_read.cold (STB_LOCAL)
ffffffff81a704b0-ffffffff81a7058a: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1759
Inline: False
```
**Symbols:**

```
ffffffff81f00b6b-ffffffff81f00b91: nvmem_device_cell_read.cold (STB_LOCAL)
ffffffff81be1420-ffffffff81be152f: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8cd30)
Location: drivers/nvmem/core.c:1762
Inline: False
```
**Symbols:**

```
ffffffff81d8cd30-ffffffff81d8ce59: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfbb20)
Location: drivers/nvmem/core.c:1944
Inline: False
```
**Symbols:**

```
ffffffff81dfbb20-ffffffff81dfbc6f: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb2640)
Location: drivers/nvmem/core.c:1987
Inline: False
```
**Symbols:**

```
ffffffff81eb2640-ffffffff81eb278f: nvmem_device_cell_read (STB_GLOBAL)
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
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9f300)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
ffff800010b9f300-ffff800010b9f3a8: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c8105c)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
c0c8105c-c0c810f0: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c727f0)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
c000000000c727f0-c000000000c728c0: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000737580)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
ffffffe000737580-ffffffe0007375ec: nvmem_device_cell_read (STB_GLOBAL)
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
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2580)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
ffffffff818a2580-ffffffff818a2601: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185dcf0)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
ffffffff8185dcf0-ffffffff8185dd71: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f3b70)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
ffffffff818f3b70-ffffffff818f3bf1: nvmem_device_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t nvmem_device_cell_read(struct nvmem_device *nvmem, struct nvmem_cell_info *info, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914c10)
Location: drivers/nvmem/core.c:1167
Inline: False
```
**Symbols:**

```
ffffffff81914c10-ffffffff81914c91: nvmem_device_cell_read (STB_GLOBAL)
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
