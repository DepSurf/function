# Function: <code>dev_dax_resize</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t dev_dax_resize(struct dax_region *dax_region, struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81834530)
Location: drivers/dax/bus.c:933
Inline: False
Direct callers:
  - drivers/dax/bus.c:size_store
```
**Symbols:**

```
ffffffff81834530-ffffffff81834857: dev_dax_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t dev_dax_resize(struct dax_region *dax_region, struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81817700)
Location: drivers/dax/bus.c:934
Inline: False
Direct callers:
  - drivers/dax/bus.c:size_store
```
**Symbols:**

```
ffffffff81817700-ffffffff81817a28: dev_dax_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t dev_dax_resize(struct dax_region *dax_region, struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:932
Inline: False
Direct callers:
  - drivers/dax/bus.c:size_store
```
**Symbols:**

```
ffffffff818a1d50-ffffffff818a2084: dev_dax_resize (STB_LOCAL)
ffffffff81d0b97d-ffffffff81d0b991: dev_dax_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t dev_dax_resize(struct dax_region *dax_region, struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:962
Inline: False
Direct callers:
  - drivers/dax/bus.c:size_store
```
**Symbols:**

```
ffffffff819eb510-ffffffff819eb876: dev_dax_resize (STB_LOCAL)
ffffffff81ed479e-ffffffff81ed47b2: dev_dax_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t dev_dax_resize(struct dax_region *dax_region, struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:962
Inline: False
Direct callers:
  - drivers/dax/bus.c:size_store
```
**Symbols:**

```
ffffffff81b680b0-ffffffff81b68416: dev_dax_resize (STB_LOCAL)
ffffffff8209b61e-ffffffff8209b632: dev_dax_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t dev_dax_resize(struct dax_region *dax_region, struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:992
Inline: False
Direct callers:
  - drivers/dax/bus.c:size_store
```
**Symbols:**

```
ffffffff81bbb550-ffffffff81bbb8a7: dev_dax_resize (STB_LOCAL)
ffffffff8211c4ea-ffffffff8211c4ff: dev_dax_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t dev_dax_resize(struct dax_region *dax_region, struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:993
Inline: False
Direct callers:
  - drivers/dax/bus.c:size_store
```
**Symbols:**

```
ffffffff81c0fc90-ffffffff81c0ffe7: dev_dax_resize (STB_LOCAL)
ffffffff821fa371-ffffffff821fa386: dev_dax_resize.cold (STB_LOCAL)
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
