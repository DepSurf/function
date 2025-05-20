# Function: <code>default_alloc</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ioasid_t default_alloc(ioasid_t min, ioasid_t max, void *opaque);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:77
Inline: False
```
**Symbols:**

```
ffffffff81792e40-ffffffff81792edf: default_alloc (STB_LOCAL)
ffffffff817933e9-ffffffff81793403: default_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ioasid_t default_alloc(ioasid_t min, ioasid_t max, void *opaque);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:78
Inline: False
```
**Symbols:**

```
ffffffff817bf7d0-ffffffff817bf86f: default_alloc (STB_LOCAL)
ffffffff81c0d74f-ffffffff81c0d769: default_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ioasid_t default_alloc(ioasid_t min, ioasid_t max, void *opaque);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:78
Inline: False
```
**Symbols:**

```
ffffffff817a29f0-ffffffff817a2a8d: default_alloc (STB_LOCAL)
ffffffff81bffab8-ffffffff81bffad2: default_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ioasid_t default_alloc(ioasid_t min, ioasid_t max, void *opaque);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:78
Inline: False
```
**Symbols:**

```
ffffffff8182bd30-ffffffff8182bdcd: default_alloc (STB_LOCAL)
ffffffff81d01f93-ffffffff81d01fad: default_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ioasid_t default_alloc(ioasid_t min, ioasid_t max, void *opaque);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:77
Inline: False
```
**Symbols:**

```
ffffffff8196d580-ffffffff8196d632: default_alloc (STB_LOCAL)
ffffffff81eca54d-ffffffff81eca566: default_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ioasid_t default_alloc(ioasid_t min, ioasid_t max, void *opaque);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81ad7e00)
Location: drivers/iommu/ioasid.c:77
Inline: False
```
**Symbols:**

```
ffffffff81ad7e00-ffffffff81ad7ec6: default_alloc (STB_LOCAL)
```
</details>
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
</ul>
