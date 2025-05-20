# Function: <code>acpi_processor_throttling_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814add1e)
Location: drivers/acpi/processor_throttling.c:221
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814fd6e8)
Location: drivers/acpi/processor_throttling.c:221
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815203d6)
Location: drivers/acpi/processor_throttling.c:221
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8153171b)
Location: drivers/acpi/processor_throttling.c:221
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81592520)
Location: drivers/acpi/processor_throttling.c:221
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff81592520-ffffffff815926e1: acpi_processor_throttling_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:221
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff815c98d0-ffffffff815c9a6d: acpi_processor_throttling_notifier (STB_LOCAL)
ffffffff815cad91-ffffffff815cadb3: acpi_processor_throttling_notifier.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:221
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff815e2eb0-ffffffff815e304d: acpi_processor_throttling_notifier (STB_LOCAL)
ffffffff815e4371-ffffffff815e4393: acpi_processor_throttling_notifier.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:208
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff81614a40-ffffffff81614be3: acpi_processor_throttling_notifier (STB_LOCAL)
ffffffff81615f12-ffffffff81615f45: acpi_processor_throttling_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:208
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff81635f30-ffffffff816360d3: acpi_processor_throttling_notifier (STB_LOCAL)
ffffffff81637402-ffffffff81637435: acpi_processor_throttling_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:208
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff816e3100-ffffffff816e3296: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
ffffffff816e4288-ffffffff816e42aa: acpi_processor_throttling_notifier.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:207
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff81700d60-ffffffff81700ef6: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
ffffffff81c02c13-ffffffff81c02c35: acpi_processor_throttling_notifier.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:202
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff816e2680-ffffffff816e278f: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
ffffffff81bf4616-ffffffff81bf4641: acpi_processor_throttling_notifier.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:200
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff8175aed0-ffffffff8175b01f: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
ffffffff81cf160c-ffffffff81cf162f: acpi_processor_throttling_notifier.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:200
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff8188eac0-ffffffff8188ec49: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
ffffffff81eb965a-ffffffff81eb967d: acpi_processor_throttling_notifier.isra.0.cold (STB_LOCAL)
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
In drivers/acpi/processor_throttling.c (ffffffff819d62a0)
Location: drivers/acpi/processor_throttling.c:198
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff819d62a0-ffffffff819d644e: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_throttling.c (ffffffff81a1dbe0)
Location: drivers/acpi/processor_throttling.c:198
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff81a1dbe0-ffffffff81a1dd8e: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_throttling.c (ffffffff81a68ef0)
Location: drivers/acpi/processor_throttling.c:198
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff81a68ef0-ffffffff81a6909e: acpi_processor_throttling_notifier.isra.0 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81605934)
Location: drivers/acpi/processor_throttling.c:208
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
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
In drivers/acpi/processor_throttling.c (ffffffff815f0a84)
Location: drivers/acpi/processor_throttling.c:208
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:208
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff8162a210-ffffffff8162a3b3: acpi_processor_throttling_notifier (STB_LOCAL)
ffffffff8162b6e2-ffffffff8162b715: acpi_processor_throttling_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:208
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
**Symbols:**

```
ffffffff816440b0-ffffffff81644253: acpi_processor_throttling_notifier (STB_LOCAL)
ffffffff81645582-ffffffff816455b5: acpi_processor_throttling_notifier.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
