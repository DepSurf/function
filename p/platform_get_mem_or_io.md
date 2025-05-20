# Function: <code>platform_get_mem_or_io</code>

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
struct resource *platform_get_mem_or_io(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d0340)
Location: drivers/base/platform.c:68
Inline: False
```
**Symbols:**

```
ffffffff817d0340-ffffffff817d038d: platform_get_mem_or_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *platform_get_mem_or_io(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b3d60)
Location: drivers/base/platform.c:68
Inline: False
```
**Symbols:**

```
ffffffff817b3d60-ffffffff817b3dad: platform_get_mem_or_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *platform_get_mem_or_io(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183d240)
Location: drivers/base/platform.c:68
Inline: False
```
**Symbols:**

```
ffffffff8183d240-ffffffff8183d28d: platform_get_mem_or_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct resource *platform_get_mem_or_io(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8197fe60)
Location: drivers/base/platform.c:70
Inline: False
```
**Symbols:**

```
ffffffff8197fe60-ffffffff8197feb3: platform_get_mem_or_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct resource *platform_get_mem_or_io(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aed7b0)
Location: drivers/base/platform.c:70
Inline: False
```
**Symbols:**

```
ffffffff81aed7b0-ffffffff81aed803: platform_get_mem_or_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct resource *platform_get_mem_or_io(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3bb40)
Location: drivers/base/platform.c:70
Inline: False
```
**Symbols:**

```
ffffffff81b3bb40-ffffffff81b3bb93: platform_get_mem_or_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct resource *platform_get_mem_or_io(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b93690)
Location: drivers/base/platform.c:70
Inline: False
```
**Symbols:**

```
ffffffff81b93690-ffffffff81b936e3: platform_get_mem_or_io (STB_GLOBAL)
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
