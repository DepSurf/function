# Function: <code>nvmem_cell_drop</code>

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
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a53d0)
Location: drivers/nvmem/core.c:303
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:nvmem_unregister
```
**Symbols:**

```
ffffffff817a53d0-ffffffff817a5427: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181c540)
Location: drivers/nvmem/core.c:303
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:nvmem_unregister
```
**Symbols:**

```
ffffffff8181c540-ffffffff8181c597: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81866660)
Location: drivers/nvmem/core.c:303
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:nvmem_unregister
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff81866660-ffffffff818666b7: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886360)
Location: drivers/nvmem/core.c:323
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffff81886360-ffffffff818863d3: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d08a0)
Location: drivers/nvmem/core.c:111
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffff818d08a0-ffffffff818d0918: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81902e90)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffff81902e90-ffffffff81902f08: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9f30)
Location: drivers/nvmem/core.c:331
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff819d9f30-ffffffff819d9faa: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9180)
Location: drivers/nvmem/core.c:421
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff819d9180-ffffffff819d91fa: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf2e0)
Location: drivers/nvmem/core.c:421
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff819bf2e0-ffffffff819bf35a: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6e7b0)
Location: drivers/nvmem/core.c:427
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff81a6e7b0-ffffffff81a6e82a: nvmem_cell_drop (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9ebd8)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffff800010b9ebd8-ffff800010b9ec5c: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c809c0)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
c0c809c0-c0c80a38: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c71d60)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
c000000000c71d60-c000000000c71e38: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000736ed4)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffe000736ed4-ffffffe000736f5a: nvmem_cell_drop (STB_LOCAL)
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
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a22c0)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffff818a22c0-ffffffff818a2338: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185da30)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffff8185da30-ffffffff8185daa8: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f38b0)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffff818f38b0-ffffffff818f3928: nvmem_cell_drop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvmem_cell_drop(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914950)
Location: drivers/nvmem/core.c:106
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
```
**Symbols:**

```
ffffffff81914950-ffffffff819149c8: nvmem_cell_drop (STB_LOCAL)
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
