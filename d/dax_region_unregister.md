# Function: <code>dax_region_unregister</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817403a0)
Location: drivers/dax/bus.c:219
Inline: False
```
**Symbols:**

```
ffffffff817403a0-ffffffff817403d5: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817645a0)
Location: drivers/dax/bus.c:219
Inline: False
```
**Symbols:**

```
ffffffff817645a0-ffffffff817645d5: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff8182428b)
Location: drivers/dax/bus.c:219
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81824380-ffffffff818243dc: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff8183417c)
Location: drivers/dax/bus.c:534
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81833cc0-ffffffff81833d1c: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81817365)
Location: drivers/dax/bus.c:535
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81816eb0-ffffffff81816f0c: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a1500)
Location: drivers/dax/bus.c:533
Inline: True
```
**Symbols:**

```
ffffffff818a1500-ffffffff818a155c: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819eb0e0)
Location: drivers/dax/bus.c:563
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff819eabf0-ffffffff819eac66: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b67c40)
Location: drivers/dax/bus.c:563
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81b676f0-ffffffff81b67766: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bba3d0)
Location: drivers/dax/bus.c:592
Inline: False
Direct callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81bba3d0-ffffffff81bba446: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c0e7a0)
Location: drivers/dax/bus.c:593
Inline: False
Direct callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81c0e7a0-ffffffff81c0e816: dax_region_unregister (STB_LOCAL)
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
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffff800010963d70)
Location: drivers/dax/bus.c:219
Inline: False
Direct callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffff800010963d70-ffff800010963db0: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c0a3a9bc)
Location: drivers/dax/bus.c:219
Inline: False
```
**Symbols:**

```
c0a3a9bc-c0a3a9f0: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c000000000a1a520)
Location: drivers/dax/bus.c:219
Inline: False
Direct callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
c000000000a1a520-c000000000a1a570: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffe0005d174e)
Location: drivers/dax/bus.c:219
Inline: False
Direct callers:
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffe0005d174e-ffffffe0005d17a6: dax_region_unregister (STB_LOCAL)
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
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81718c90)
Location: drivers/dax/bus.c:219
Inline: False
```
**Symbols:**

```
ffffffff81718c90-ffffffff81718cc5: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f11c0)
Location: drivers/dax/bus.c:219
Inline: False
```
**Symbols:**

```
ffffffff816f11c0-ffffffff816f11f5: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81757a60)
Location: drivers/dax/bus.c:219
Inline: False
```
**Symbols:**

```
ffffffff81757a60-ffffffff81757a95: dax_region_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dax_region_unregister(void *region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81772f00)
Location: drivers/dax/bus.c:219
Inline: False
```
**Symbols:**

```
ffffffff81772f00-ffffffff81772f35: dax_region_unregister (STB_LOCAL)
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
