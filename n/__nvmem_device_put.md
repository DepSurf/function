# Function: <code>__nvmem_device_put</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5890)
Location: drivers/nvmem/core.c:593
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff817a5890-ffffffff817a58c0: __nvmem_device_put.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181ca00)
Location: drivers/nvmem/core.c:595
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff8181ca00-ffffffff8181ca30: __nvmem_device_put.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81866b00)
Location: drivers/nvmem/core.c:669
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81866b00-ffffffff81866b30: __nvmem_device_put.isra.13 (STB_LOCAL)
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
In drivers/nvmem/core.c (ffffffff81886fee)
Location: drivers/nvmem/core.c:818
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0f80)
Location: drivers/nvmem/core.c:565
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff818d0f80-ffffffff818d0fbc: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903380)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81903380-ffffffff819033bc: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da700)
Location: drivers/nvmem/core.c:805
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff819da700-ffffffff819da75c: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9590)
Location: drivers/nvmem/core.c:980
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff819d9590-ffffffff819d95ec: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf830)
Location: drivers/nvmem/core.c:983
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff819bf830-ffffffff819bf88c: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6ee80)
Location: drivers/nvmem/core.c:994
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81a6ee80-ffffffff81a6eedc: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81bdff00)
Location: drivers/nvmem/core.c:974
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81bdff00-ffffffff81bdff7a: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b6c0)
Location: drivers/nvmem/core.c:972
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81d8b6c0-ffffffff81d8b73a: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9c20)
Location: drivers/nvmem/core.c:1122
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81df9c20-ffffffff81df9c9a: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb1050)
Location: drivers/nvmem/core.c:1133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81eb1050-ffffffff81eb110f: __nvmem_device_put (STB_LOCAL)
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
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9ef68)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffff800010b9ef68-ffff800010b9efb8: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80d6c)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
c0c80d6c-c0c80db0: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c72380)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
c000000000c72380-c000000000c72414: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000737260)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffe000737260-ffffffe0007372ba: __nvmem_device_put (STB_LOCAL)
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
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a27b0)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff818a27b0-ffffffff818a27ec: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185df20)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff8185df20-ffffffff8185df5c: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f3da0)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff818f3da0-ffffffff818f3ddc: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __nvmem_device_put(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914e40)
Location: drivers/nvmem/core.c:562
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
```
**Symbols:**

```
ffffffff81914e40-ffffffff81914e7c: __nvmem_device_put (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
