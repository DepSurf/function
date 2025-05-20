# Function: <code>of_nvmem_device_get</code>

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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:150
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:160
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:160
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:214
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:221
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:221
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:237
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:238
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:242
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:256
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:257
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:250
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:258
Inline: True
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
struct nvmem_device *of_nvmem_device_get(struct device_node *np, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9eef8)
Location: drivers/nvmem/core.c:579
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_get
```
**Symbols:**

```
ffff800010b9eef8-ffff800010b9ef68: of_nvmem_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nvmem_device *of_nvmem_device_get(struct device_node *np, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80c60)
Location: drivers/nvmem/core.c:579
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_get
```
**Symbols:**

```
c0c80c60-c0c80cbc: of_nvmem_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nvmem_device *of_nvmem_device_get(struct device_node *np, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c722c0)
Location: drivers/nvmem/core.c:579
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_get
```
**Symbols:**

```
c000000000c722c0-c000000000c72378: of_nvmem_device_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nvmem_device *of_nvmem_device_get(struct device_node *np, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe0007371fa)
Location: drivers/nvmem/core.c:579
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_get
```
**Symbols:**

```
ffffffe0007371fa-ffffffe000737260: of_nvmem_device_get (STB_GLOBAL)
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:221
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:221
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:221
Inline: True
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
In drivers/nvmem/core.c (0)
Location: include/linux/nvmem-consumer.h:221
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
