# Function: <code>nvmem_cell_get_from_lookup</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886960)
Location: drivers/nvmem/core.c:951
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81886960-ffffffff81886b6e: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0ff0)
Location: drivers/nvmem/core.c:700
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff818d0ff0-ffffffff818d1138: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819033f0)
Location: drivers/nvmem/core.c:697
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff819033f0-ffffffff81903538: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da790)
Location: drivers/nvmem/core.c:956
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff819da790-ffffffff819da8df: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9620)
Location: drivers/nvmem/core.c:1134
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff819d9620-ffffffff819d976f: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf8c0)
Location: drivers/nvmem/core.c:1137
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff819bf8c0-ffffffff819bfa0f: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6ef10)
Location: drivers/nvmem/core.c:1148
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81a6ef10-ffffffff81a6f05f: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be0110)
Location: drivers/nvmem/core.c:1151
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81be0110-ffffffff81be02e6: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b930)
Location: drivers/nvmem/core.c:1149
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81d8b930-ffffffff81d8bb06: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9fa0)
Location: drivers/nvmem/core.c:1301
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81df9fa0-ffffffff81dfa17e: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb1180)
Location: drivers/nvmem/core.c:1312
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81eb1180-ffffffff81eb12f3: nvmem_cell_get_from_lookup (STB_LOCAL)
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
In drivers/nvmem/core.c (ffff800010b9f5c0)
Location: drivers/nvmem/core.c:697
Inline: True
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
In drivers/nvmem/core.c (c0c812a8)
Location: drivers/nvmem/core.c:697
Inline: True
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
In drivers/nvmem/core.c (c000000000c72acc)
Location: drivers/nvmem/core.c:697
Inline: True
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
In drivers/nvmem/core.c (ffffffe000737826)
Location: drivers/nvmem/core.c:697
Inline: True
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
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2820)
Location: drivers/nvmem/core.c:697
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff818a2820-ffffffff818a2968: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185df90)
Location: drivers/nvmem/core.c:697
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff8185df90-ffffffff8185e0d8: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f3e10)
Location: drivers/nvmem/core.c:697
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff818f3e10-ffffffff818f3f58: nvmem_cell_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nvmem_cell *nvmem_cell_get_from_lookup(struct device *dev, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914eb0)
Location: drivers/nvmem/core.c:697
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81914eb0-ffffffff81914ff8: nvmem_cell_get_from_lookup (STB_LOCAL)
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
