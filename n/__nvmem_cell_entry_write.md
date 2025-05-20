# Function: <code>__nvmem_cell_entry_write</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __nvmem_cell_entry_write(struct nvmem_cell_entry *cell, void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1523
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff81be1660-ffffffff81be17bd: __nvmem_cell_entry_write (STB_LOCAL)
ffffffff81f00b91-ffffffff81f00ba6: __nvmem_cell_entry_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __nvmem_cell_entry_write(struct nvmem_cell_entry *cell, void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1526
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff81d8cfb0-ffffffff81d8d10d: __nvmem_cell_entry_write (STB_LOCAL)
ffffffff820aa9c6-ffffffff820aa9db: __nvmem_cell_entry_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __nvmem_cell_entry_write(struct nvmem_cell_entry *cell, void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1700
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff81dfb570-ffffffff81dfb710: __nvmem_cell_entry_write (STB_LOCAL)
ffffffff8212bf02-ffffffff8212bf17: __nvmem_cell_entry_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __nvmem_cell_entry_write(struct nvmem_cell_entry *cell, void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1743
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_cell_write
```
**Symbols:**

```
ffffffff81eb2330-ffffffff81eb24d0: __nvmem_cell_entry_write (STB_LOCAL)
ffffffff8220dbfe-ffffffff8220dc13: __nvmem_cell_entry_write.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
