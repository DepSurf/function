# Function: <code>nvmem_access_with_keepouts</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9c40)
Location: drivers/nvmem/core.c:95
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff819d9c40-ffffffff819d9e5f: nvmem_access_with_keepouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bfb90)
Location: drivers/nvmem/core.c:95
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff819bfb90-ffffffff819bfdae: nvmem_access_with_keepouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6f280)
Location: drivers/nvmem/core.c:95
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:nvmem_cell_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff81a6f280-ffffffff81a6f49e: nvmem_access_with_keepouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be0470)
Location: drivers/nvmem/core.c:100
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff81be0470-ffffffff81be06dc: nvmem_access_with_keepouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8bc10)
Location: drivers/nvmem/core.c:100
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff81d8bc10-ffffffff81d8be7c: nvmem_access_with_keepouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfa280)
Location: drivers/nvmem/core.c:108
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff81dfa280-ffffffff81dfa4ec: nvmem_access_with_keepouts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device *nvmem, unsigned int offset, void *val, size_t bytes, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb06b0)
Location: drivers/nvmem/core.c:82
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_write
  - drivers/nvmem/core.c:nvmem_device_read
  - drivers/nvmem/core.c:__nvmem_cell_entry_write
  - drivers/nvmem/core.c:bin_attr_nvmem_write
```
**Symbols:**

```
ffffffff81eb06b0-ffffffff81eb091c: nvmem_access_with_keepouts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
