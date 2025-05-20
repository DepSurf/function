# Function: <code>nvmem_device_remove_all_cells</code>

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
In drivers/nvmem/core.c (ffffffff817a5475)
Location: drivers/nvmem/core.c:311
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_unregister
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
In drivers/nvmem/core.c (ffffffff8181c5e5)
Location: drivers/nvmem/core.c:311
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_unregister
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
In drivers/nvmem/core.c (ffffffff81866732)
Location: drivers/nvmem/core.c:311
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818863e0)
Location: drivers/nvmem/core.c:334
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff818863e0-ffffffff8188642b: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0920)
Location: drivers/nvmem/core.c:122
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff818d0920-ffffffff818d096b: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81902f10)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff81902f10-ffffffff81902f5b: nvmem_device_remove_all_cells (STB_LOCAL)
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
In drivers/nvmem/core.c (ffffffff819da6a1)
Location: drivers/nvmem/core.c:342
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_release
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
In drivers/nvmem/core.c (ffffffff819d9531)
Location: drivers/nvmem/core.c:432
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_release
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
In drivers/nvmem/core.c (ffffffff819bf7d1)
Location: drivers/nvmem/core.c:432
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_release
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
In drivers/nvmem/core.c (ffffffff81a6ee21)
Location: drivers/nvmem/core.c:438
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_release
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
In drivers/nvmem/core.c (ffffffff81bdfe91)
Location: drivers/nvmem/core.c:443
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_release
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
In drivers/nvmem/core.c (ffffffff81d8b641)
Location: drivers/nvmem/core.c:443
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9540)
Location: drivers/nvmem/core.c:451
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81df9540-ffffffff81df9609: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eafaf0)
Location: drivers/nvmem/core.c:535
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81eafaf0-ffffffff81eafbb9: nvmem_device_remove_all_cells (STB_LOCAL)
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
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9ec60)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffff800010b9ec60-ffff800010b9ecb8: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80a38)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
c0c80a38-c0c80a84: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c71e40)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
c000000000c71e40-c000000000c71eb4: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000736f5a)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffe000736f5a-ffffffe000736fac: nvmem_device_remove_all_cells (STB_LOCAL)
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
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2340)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff818a2340-ffffffff818a238b: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185dab0)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff8185dab0-ffffffff8185dafb: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f3930)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff818f3930-ffffffff818f397b: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvmem_device_remove_all_cells(const struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819149d0)
Location: drivers/nvmem/core.c:117
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff819149d0-ffffffff81914a1b: nvmem_device_remove_all_cells (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
