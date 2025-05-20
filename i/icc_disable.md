# Function: <code>icc_disable</code>

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
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dce70)
Location: drivers/interconnect/core.c:671
Inline: False
```
**Symbols:**

```
ffffffff819dce70-ffffffff819dce82: icc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dc590)
Location: drivers/interconnect/core.c:702
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_disable
```
**Symbols:**

```
ffffffff819dc590-ffffffff819dc5a2: icc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c2810)
Location: drivers/interconnect/core.c:702
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_disable
```
**Symbols:**

```
ffffffff819c2810-ffffffff819c2822: icc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a720c0)
Location: drivers/interconnect/core.c:702
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_disable
```
**Symbols:**

```
ffffffff81a720c0-ffffffff81a720d2: icc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be3bb0)
Location: drivers/interconnect/core.c:702
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_disable
```
**Symbols:**

```
ffffffff81be3bb0-ffffffff81be3bca: icc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8f8d0)
Location: drivers/interconnect/core.c:702
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81d8f8d0-ffffffff81d8f8ea: icc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfdeb0)
Location: drivers/interconnect/core.c:701
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81dfdeb0-ffffffff81dfdeca: icc_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int icc_disable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb4910)
Location: drivers/interconnect/core.c:768
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81eb4910-ffffffff81eb492a: icc_disable (STB_GLOBAL)
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
