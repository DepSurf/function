# Function: <code>nvmem_cell_prepare_write_buffer</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5c22)
Location: drivers/nvmem/core.c:1030
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181cda9)
Location: drivers/nvmem/core.c:1032
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81866e49)
Location: drivers/nvmem/core.c:1105
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886ce9)
Location: drivers/nvmem/core.c:1241
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d1b11)
Location: drivers/nvmem/core.c:996
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903f11)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da190)
Location: drivers/nvmem/core.c:1253
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff819da190-ffffffff819da368: nvmem_cell_prepare_write_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9f40)
Location: drivers/nvmem/core.c:1431
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff819d9f40-ffffffff819da0e7: nvmem_cell_prepare_write_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bfe90)
Location: drivers/nvmem/core.c:1434
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff819bfe90-ffffffff819c001e: nvmem_cell_prepare_write_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1446
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff81a6f580-ffffffff81a6f766: nvmem_cell_prepare_write_buffer (STB_LOCAL)
ffffffff81d344e8-ffffffff81d345db: nvmem_cell_prepare_write_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1470
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
```
**Symbols:**

```
ffffffff81be0840-ffffffff81be0a3e: nvmem_cell_prepare_write_buffer (STB_LOCAL)
ffffffff81f00921-ffffffff81f009fd: nvmem_cell_prepare_write_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1473
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
```
**Symbols:**

```
ffffffff81d8c010-ffffffff81d8c20e: nvmem_cell_prepare_write_buffer (STB_LOCAL)
ffffffff820aa7d6-ffffffff820aa8b2: nvmem_cell_prepare_write_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1647
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
```
**Symbols:**

```
ffffffff81dfa680-ffffffff81dfa88c: nvmem_cell_prepare_write_buffer (STB_LOCAL)
ffffffff8212bce4-ffffffff8212bdee: nvmem_cell_prepare_write_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry *cell, u8 *_buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1690
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
```
**Symbols:**

```
ffffffff81eb0ab0-ffffffff81eb0cbc: nvmem_cell_prepare_write_buffer (STB_LOCAL)
ffffffff8220d995-ffffffff8220da9f: nvmem_cell_prepare_write_buffer.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9f850)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c81e0c)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c74068)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000737a32)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a3341)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185eab1)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f4931)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819159d1)
Location: drivers/nvmem/core.c:993
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nvmem_cell *cell</code> ➡️ <code>struct nvmem_cell_entry *cell</code>
</li>
</ul>
</details>
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
