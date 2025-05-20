# Function: <code>__nvmem_device_get</code>

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
In drivers/nvmem/core.c (ffffffff817a5950)
Location: drivers/nvmem/core.c:547
Inline: True
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff817a5950-ffffffff817a5a5f: __nvmem_device_get.constprop.16 (STB_LOCAL)
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
In drivers/nvmem/core.c (ffffffff8181cac0)
Location: drivers/nvmem/core.c:549
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff8181cac0-ffffffff8181cbdd: __nvmem_device_get.constprop.16 (STB_LOCAL)
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
In drivers/nvmem/core.c (ffffffff81866bc5)
Location: drivers/nvmem/core.c:623
Inline: True
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
In drivers/nvmem/core.c (ffffffff81886a03)
Location: drivers/nvmem/core.c:794
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:540
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff818d0e40-ffffffff818d0ed9: __nvmem_device_get.constprop.0 (STB_LOCAL)
ffffffff818d1dc5-ffffffff818d1df8: __nvmem_device_get.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:537
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff81903240-ffffffff819032e0: __nvmem_device_get.constprop.0 (STB_LOCAL)
ffffffff81904174-ffffffff819041a7: __nvmem_device_get.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:777
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff819da490-ffffffff819da561: __nvmem_device_get (STB_LOCAL)
ffffffff819db83f-ffffffff819db872: __nvmem_device_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:952
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff819d9320-ffffffff819d93f1: __nvmem_device_get (STB_LOCAL)
ffffffff81c3019f-ffffffff81c301d2: __nvmem_device_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:955
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff819bf3f0-ffffffff819bf4c1: __nvmem_device_get (STB_LOCAL)
ffffffff81c22405-ffffffff81c22438: __nvmem_device_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:966
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff81a6ea80-ffffffff81a6eb51: __nvmem_device_get (STB_LOCAL)
ffffffff81d34485-ffffffff81d344b8: __nvmem_device_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:946
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff81bdfaa0-ffffffff81bdfb72: __nvmem_device_get (STB_LOCAL)
ffffffff81f008c0-ffffffff81f008f1: __nvmem_device_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b1d0)
Location: drivers/nvmem/core.c:944
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff81d8b1d0-ffffffff81d8b2d4: __nvmem_device_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9950)
Location: drivers/nvmem/core.c:1094
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff81df9950-ffffffff81df9a54: __nvmem_device_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nvmem_device *__nvmem_device_get(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb0260)
Location: drivers/nvmem/core.c:1105
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
  - drivers/nvmem/core.c:nvmem_device_find
```
**Symbols:**

```
ffffffff81eb0260-ffffffff81eb0364: __nvmem_device_get (STB_LOCAL)
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
struct nvmem_device *__nvmem_device_get(struct device_node *np, const char *nvmem_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9ede0)
Location: drivers/nvmem/core.c:537
Inline: False
Direct callers:
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:of_nvmem_device_get
```
**Symbols:**

```
ffff800010b9ede0-ffff800010b9eef4: __nvmem_device_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nvmem_device *__nvmem_device_get(struct device_node *np, const char *nvmem_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80b74)
Location: drivers/nvmem/core.c:537
Inline: False
Direct callers:
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:of_nvmem_device_get
```
**Symbols:**

```
c0c80b74-c0c80c60: __nvmem_device_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nvmem_device *__nvmem_device_get(struct device_node *np, const char *nvmem_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c72110)
Location: drivers/nvmem/core.c:537
Inline: False
Direct callers:
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:of_nvmem_device_get
```
**Symbols:**

```
c000000000c72110-c000000000c722b4: __nvmem_device_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nvmem_device *__nvmem_device_get(struct device_node *np, const char *nvmem_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe0007370ee)
Location: drivers/nvmem/core.c:537
Inline: False
Direct callers:
  - drivers/nvmem/core.c:of_nvmem_cell_get
  - drivers/nvmem/core.c:of_nvmem_device_get
```
**Symbols:**

```
ffffffe0007370ee-ffffffe0007371fa: __nvmem_device_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:537
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff818a2670-ffffffff818a2710: __nvmem_device_get.constprop.0 (STB_LOCAL)
ffffffff818a35a4-ffffffff818a35d7: __nvmem_device_get.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:537
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff8185dde0-ffffffff8185de80: __nvmem_device_get.constprop.0 (STB_LOCAL)
ffffffff8185ed14-ffffffff8185ed47: __nvmem_device_get.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:537
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff818f3c60-ffffffff818f3d00: __nvmem_device_get.constprop.0 (STB_LOCAL)
ffffffff818f4b94-ffffffff818f4bc7: __nvmem_device_get.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:537
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff81914d00-ffffffff81914da0: __nvmem_device_get.constprop.0 (STB_LOCAL)
ffffffff81915c34-ffffffff81915c67: __nvmem_device_get.constprop.0.cold (STB_LOCAL)
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
