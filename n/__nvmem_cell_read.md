# Function: <code>__nvmem_cell_read</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5670)
Location: drivers/nvmem/core.c:976
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff817a5670-ffffffff817a57a2: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181c7e0)
Location: drivers/nvmem/core.c:978
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff8181c7e0-ffffffff8181c915: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818668c0)
Location: drivers/nvmem/core.c:1051
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff818668c0-ffffffff818669f7: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886740)
Location: drivers/nvmem/core.c:1187
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff81886740-ffffffff81886877: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0c00)
Location: drivers/nvmem/core.c:942
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff818d0c00-ffffffff818d0d49: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903000)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff81903000-ffffffff81903149: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9fe0)
Location: drivers/nvmem/core.c:1199
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff819d9fe0-ffffffff819da12f: __nvmem_cell_read (STB_LOCAL)
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
In drivers/nvmem/core.c (ffffffff819da215)
Location: drivers/nvmem/core.c:1377
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
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
In drivers/nvmem/core.c (ffffffff819c0ce6)
Location: drivers/nvmem/core.c:1380
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
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
In drivers/nvmem/core.c (ffffffff81a70516)
Location: drivers/nvmem/core.c:1392
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be14a8)
Location: drivers/nvmem/core.c:1409
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff81bdf8f0-ffffffff81bdfaa0: __nvmem_cell_read.part.0 (STB_LOCAL)
ffffffff81f007df-ffffffff81f008c0: __nvmem_cell_read.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8cdb4)
Location: drivers/nvmem/core.c:1412
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff81d8b010-ffffffff81d8b1c0: __nvmem_cell_read.part.0 (STB_LOCAL)
ffffffff820aa6f5-ffffffff820aa7d6: __nvmem_cell_read.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfbbca)
Location: drivers/nvmem/core.c:1585
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff81df9790-ffffffff81df9932: __nvmem_cell_read.part.0 (STB_LOCAL)
ffffffff8212bc03-ffffffff8212bce4: __nvmem_cell_read.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb26ea)
Location: drivers/nvmem/core.c:1628
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff81eb0020-ffffffff81eb01c2: __nvmem_cell_read.part.0 (STB_LOCAL)
ffffffff8220d8b4-ffffffff8220d995: __nvmem_cell_read.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9f190)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffff800010b9f190-ffff800010b9f300: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80f20)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
c0c80f20-c0c8105c: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c72610)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
c000000000c72610-c000000000c727e8: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000737456)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffe000737456-ffffffe000737580: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2430)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff818a2430-ffffffff818a2579: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185dba0)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff8185dba0-ffffffff8185dce9: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f3a20)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff818f3a20-ffffffff818f3b69: __nvmem_cell_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __nvmem_cell_read(struct nvmem_device *nvmem, struct nvmem_cell *cell, void *buf, size_t *len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914ac0)
Location: drivers/nvmem/core.c:939
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_read
```
**Symbols:**

```
ffffffff81914ac0-ffffffff81914c09: __nvmem_cell_read (STB_LOCAL)
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
