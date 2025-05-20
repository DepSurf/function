# Function: <code>nvmem_reg_read</code>

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
In drivers/nvmem/core.c (ffffffff817a52c1)
Location: drivers/nvmem/core.c:70
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_read
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
In drivers/nvmem/core.c (ffffffff8181c431)
Location: drivers/nvmem/core.c:70
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_read
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
In drivers/nvmem/core.c (ffffffff81866581)
Location: drivers/nvmem/core.c:70
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_read
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
In drivers/nvmem/core.c (ffffffff81886151)
Location: drivers/nvmem/core.c:76
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_read
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
In drivers/nvmem/core.c (ffffffff818d06d1)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (ffffffff81902aa1)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (ffffffff819d9b7a)
Location: drivers/nvmem/core.c:69
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nvmem_reg_read(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da5ab)
Location: drivers/nvmem/core.c:159
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_device_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
**Symbols:**

```
ffffffff819d9e60-ffffffff819d9e9e: nvmem_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nvmem_reg_read(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c107b)
Location: drivers/nvmem/core.c:159
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_device_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
**Symbols:**

```
ffffffff819bfdb0-ffffffff819bfdee: nvmem_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int nvmem_reg_read(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a708bb)
Location: drivers/nvmem/core.c:159
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_device_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
**Symbols:**

```
ffffffff81a6f4a0-ffffffff81a6f4de: nvmem_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int nvmem_reg_read(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be1b4b)
Location: drivers/nvmem/core.c:164
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_device_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
**Symbols:**

```
ffffffff81be06e0-ffffffff81be074b: nvmem_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int nvmem_reg_read(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d50b)
Location: drivers/nvmem/core.c:164
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_device_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
**Symbols:**

```
ffffffff81d8be90-ffffffff81d8befb: nvmem_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int nvmem_reg_read(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfbc9b)
Location: drivers/nvmem/core.c:172
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_device_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
**Symbols:**

```
ffffffff81dfa500-ffffffff81dfa56b: nvmem_reg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int nvmem_reg_read(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb29bb)
Location: drivers/nvmem/core.c:146
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_device_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_prepare_write_buffer
  - drivers/nvmem/core.c:nvmem_cell_read
  - drivers/nvmem/core.c:bin_attr_nvmem_read
```
**Symbols:**

```
ffffffff81eb0930-ffffffff81eb099b: nvmem_reg_read (STB_LOCAL)
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
In drivers/nvmem/core.c (ffff800010b9e698)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (c0c805f4)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (c000000000c71658)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (ffffffe000736a3a)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (ffffffff818a1ed1)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (ffffffff8185d641)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (ffffffff818f34c1)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
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
In drivers/nvmem/core.c (ffffffff81914561)
Location: drivers/nvmem/core.c:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
