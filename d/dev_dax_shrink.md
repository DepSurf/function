# Function: <code>dev_dax_shrink</code>

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
int dev_dax_shrink(struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81834380)
Location: drivers/dax/bus.c:867
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81834380-ffffffff81834521: dev_dax_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_dax_shrink(struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81817560)
Location: drivers/dax/bus.c:868
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81817560-ffffffff818176fe: dev_dax_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_dax_shrink(struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:866
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff818a1ba0-ffffffff818a1d4f: dev_dax_shrink (STB_LOCAL)
ffffffff81d0b969-ffffffff81d0b97d: dev_dax_shrink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_dax_shrink(struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:896
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff819eb270-ffffffff819eb44c: dev_dax_shrink (STB_LOCAL)
ffffffff81ed4789-ffffffff81ed479e: dev_dax_shrink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dev_dax_shrink(struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:896
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81b67df0-ffffffff81b67fcc: dev_dax_shrink (STB_LOCAL)
ffffffff8209b609-ffffffff8209b61e: dev_dax_shrink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dev_dax_shrink(struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:926
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81bbb290-ffffffff81bbb46c: dev_dax_shrink (STB_LOCAL)
ffffffff8211c4d5-ffffffff8211c4ea: dev_dax_shrink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_dax_shrink(struct dev_dax *dev_dax, resource_size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/bus.c (0)
Location: drivers/dax/bus.c:927
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_resize
```
**Symbols:**

```
ffffffff81c0f9d0-ffffffff81c0fbac: dev_dax_shrink (STB_LOCAL)
ffffffff821fa35c-ffffffff821fa371: dev_dax_shrink.cold (STB_LOCAL)
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
