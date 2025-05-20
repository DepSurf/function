# Function: <code>adjust_dev_dax_range</code>

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
int adjust_dev_dax_range(struct dev_dax *dev_dax, struct resource *res, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818330d0)
Location: drivers/dax/bus.c:814
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
```
**Symbols:**

```
ffffffff818330d0-ffffffff818331dc: adjust_dev_dax_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int adjust_dev_dax_range(struct dev_dax *dev_dax, struct resource *res, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818162c0)
Location: drivers/dax/bus.c:815
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
```
**Symbols:**

```
ffffffff818162c0-ffffffff818163cc: adjust_dev_dax_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int adjust_dev_dax_range(struct dev_dax *dev_dax, struct resource *res, resource_size_t size);
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
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
```
**Symbols:**

```
ffffffff818a0aa0-ffffffff818a0bb8: adjust_dev_dax_range (STB_LOCAL)
ffffffff81d0b925-ffffffff81d0b941: adjust_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int adjust_dev_dax_range(struct dev_dax *dev_dax, struct resource *res, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:843
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
```
**Symbols:**

```
ffffffff819ea110-ffffffff819ea23d: adjust_dev_dax_range (STB_LOCAL)
ffffffff81ed4734-ffffffff81ed4750: adjust_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int adjust_dev_dax_range(struct dev_dax *dev_dax, struct resource *res, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:843
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
```
**Symbols:**

```
ffffffff81b66b60-ffffffff81b66c8d: adjust_dev_dax_range (STB_LOCAL)
ffffffff8209b5b4-ffffffff8209b5d0: adjust_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int adjust_dev_dax_range(struct dev_dax *dev_dax, struct resource *res, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:873
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
```
**Symbols:**

```
ffffffff81bb9f20-ffffffff81bba047: adjust_dev_dax_range (STB_LOCAL)
ffffffff8211c483-ffffffff8211c497: adjust_dev_dax_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int adjust_dev_dax_range(struct dev_dax *dev_dax, struct resource *res, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:874
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
  - drivers/dax/bus.c:dev_dax_shrink
```
**Symbols:**

```
ffffffff81c0e580-ffffffff81c0e6a7: adjust_dev_dax_range (STB_LOCAL)
ffffffff821fa30a-ffffffff821fa31e: adjust_dev_dax_range.cold (STB_LOCAL)
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
