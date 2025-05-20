# Function: <code>nvmem_device_find</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da610)
Location: drivers/nvmem/core.c:874
Inline: False
```
**Symbols:**

```
ffffffff819da610-ffffffff819da620: nvmem_device_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d94a0)
Location: drivers/nvmem/core.c:1052
Inline: False
```
**Symbols:**

```
ffffffff819d94a0-ffffffff819d94b0: nvmem_device_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf570)
Location: drivers/nvmem/core.c:1055
Inline: False
```
**Symbols:**

```
ffffffff819bf570-ffffffff819bf580: nvmem_device_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6ec10)
Location: drivers/nvmem/core.c:1066
Inline: False
```
**Symbols:**

```
ffffffff81a6ec10-ffffffff81a6ec20: nvmem_device_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81bdfbb0)
Location: drivers/nvmem/core.c:1046
Inline: False
```
**Symbols:**

```
ffffffff81bdfbb0-ffffffff81bdfbc8: nvmem_device_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b330)
Location: drivers/nvmem/core.c:1044
Inline: False
```
**Symbols:**

```
ffffffff81d8b330-ffffffff81d8b348: nvmem_device_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9ab0)
Location: drivers/nvmem/core.c:1194
Inline: False
```
**Symbols:**

```
ffffffff81df9ab0-ffffffff81df9ac8: nvmem_device_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nvmem_device *nvmem_device_find(void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb03c0)
Location: drivers/nvmem/core.c:1205
Inline: False
```
**Symbols:**

```
ffffffff81eb03c0-ffffffff81eb03d8: nvmem_device_find (STB_GLOBAL)
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
