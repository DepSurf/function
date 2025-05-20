# Function: <code>icc_enable</code>

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
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dce50)
Location: drivers/interconnect/core.c:665
Inline: False
```
**Symbols:**

```
ffffffff819dce50-ffffffff819dce65: icc_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dc570)
Location: drivers/interconnect/core.c:696
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff819dc570-ffffffff819dc585: icc_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c27f0)
Location: drivers/interconnect/core.c:696
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff819c27f0-ffffffff819c2805: icc_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a720a0)
Location: drivers/interconnect/core.c:696
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81a720a0-ffffffff81a720b5: icc_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be3b90)
Location: drivers/interconnect/core.c:696
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81be3b90-ffffffff81be3bad: icc_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8f8a0)
Location: drivers/interconnect/core.c:696
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81d8f8a0-ffffffff81d8f8bd: icc_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfde80)
Location: drivers/interconnect/core.c:695
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81dfde80-ffffffff81dfde9d: icc_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int icc_enable(struct icc_path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb48e0)
Location: drivers/interconnect/core.c:762
Inline: False
Direct callers:
  - drivers/interconnect/bulk.c:icc_bulk_enable
```
**Symbols:**

```
ffffffff81eb48e0-ffffffff81eb48fd: icc_enable (STB_GLOBAL)
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
