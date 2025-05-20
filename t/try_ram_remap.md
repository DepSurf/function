# Function: <code>try_ram_remap</code>

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
In kernel/memremap.c (ffffffff8118b7b9)
Location: kernel/memremap.c:27
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
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
In kernel/memremap.c (ffffffff8119e3c3)
Location: kernel/memremap.c:37
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
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
In kernel/memremap.c (ffffffff811addf3)
Location: kernel/memremap.c:37
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
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
In kernel/memremap.c (ffffffff811b5295)
Location: kernel/memremap.c:37
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
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
In kernel/memremap.c (ffffffff811c8a58)
Location: kernel/memremap.c:46
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
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
In kernel/iomem.c (ffffffff811e8f93)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff811f9ca3)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff81211be2)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff8121f3d2)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *try_ram_remap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff8124b630)
Location: kernel/iomem.c:30
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff8124b630-ffffffff8124b6df: try_ram_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *try_ram_remap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81255a20)
Location: kernel/iomem.c:30
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81255a20-ffffffff81255acf: try_ram_remap (STB_LOCAL)
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
In kernel/iomem.c (ffffffff8125a0ae)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff81295ece)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *try_ram_remap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff812ebae0)
Location: kernel/iomem.c:30
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff812ebae0-ffffffff812ebba9: try_ram_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *try_ram_remap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff81355d20)
Location: kernel/iomem.c:30
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81355d20-ffffffff81355ded: try_ram_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *try_ram_remap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff813873b0)
Location: kernel/iomem.c:30
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff813873b0-ffffffff8138747d: try_ram_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *try_ram_remap(resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffff813b0d40)
Location: kernel/iomem.c:27
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff813b0d40-ffffffff813b0e3c: try_ram_remap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffff8000102abb58)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c04d8e80)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (c00000000035fac8)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (ffffffe0001d3638)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff81217a22)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff8120ac32)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff812157c2)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
In kernel/iomem.c (ffffffff812247c2)
Location: kernel/iomem.c:30
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
