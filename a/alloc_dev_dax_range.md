# Function: <code>alloc_dev_dax_range</code>

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
int alloc_dev_dax_range(struct dev_dax *dev_dax, u64 start, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81833890)
Location: drivers/dax/bus.c:753
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81833890-ffffffff81833a82: alloc_dev_dax_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_dev_dax_range(struct dev_dax *dev_dax, u64 start, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818169f0)
Location: drivers/dax/bus.c:754
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff818169f0-ffffffff81816be1: alloc_dev_dax_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int alloc_dev_dax_range(struct dev_dax *dev_dax, u64 start, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:752
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff818a1040-ffffffff818a123a: alloc_dev_dax_range (STB_LOCAL)
ffffffff81d0b955-ffffffff81d0b969: alloc_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int alloc_dev_dax_range(struct dev_dax *dev_dax, u64 start, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:782
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff819ea6f0-ffffffff819ea8fc: alloc_dev_dax_range (STB_LOCAL)
ffffffff81ed476c-ffffffff81ed4789: alloc_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int alloc_dev_dax_range(struct dev_dax *dev_dax, u64 start, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:782
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81b671a0-ffffffff81b673b1: alloc_dev_dax_range (STB_LOCAL)
ffffffff8209b5ec-ffffffff8209b609: alloc_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int alloc_dev_dax_range(struct dev_dax *dev_dax, u64 start, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:812
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81bba880-ffffffff81bbaa8c: alloc_dev_dax_range (STB_LOCAL)
ffffffff8211c4c0-ffffffff8211c4d5: alloc_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int alloc_dev_dax_range(struct dev_dax *dev_dax, u64 start, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:813
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:mapping_store
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81c0ed40-ffffffff81c0ef4c: alloc_dev_dax_range (STB_LOCAL)
ffffffff821fa347-ffffffff821fa35c: alloc_dev_dax_range.cold (STB_LOCAL)
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
