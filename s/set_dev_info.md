# Function: <code>set_dev_info</code>

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
void set_dev_info(const struct device *dev, struct dev_printk_info *dev_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81c0dbbf)
Location: drivers/base/core.c:4251
Inline: False
Direct callers:
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81c0dbbf-ffffffff81c0dcf5: set_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_dev_info(const struct device *dev, struct dev_printk_info *dev_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81bfff59)
Location: drivers/base/core.c:4478
Inline: False
Direct callers:
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81bfff59-ffffffff81c0008f: set_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_dev_info(const struct device *dev, struct dev_printk_info *dev_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81d024af)
Location: drivers/base/core.c:4543
Inline: False
Direct callers:
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81d024af-ffffffff81d025e5: set_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_dev_info(const struct device *dev, struct dev_printk_info *dev_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ecaa41)
Location: drivers/base/core.c:4577
Inline: False
Direct callers:
  - drivers/base/core.c:dev_vprintk_emit
```
**Symbols:**

```
ffffffff81ecaa41-ffffffff81ecab8b: set_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_dev_info(const struct device *dev, struct dev_printk_info *dev_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae0e60)
Location: drivers/base/core.c:4796
Inline: False
Direct callers:
  - drivers/base/core.c:dev_printk_emit
```
**Symbols:**

```
ffffffff81ae0e60-ffffffff81ae101b: set_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_dev_info(const struct device *dev, struct dev_printk_info *dev_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2f0b0)
Location: drivers/base/core.c:4801
Inline: False
Direct callers:
  - drivers/base/core.c:dev_printk_emit
```
**Symbols:**

```
ffffffff81b2f0b0-ffffffff81b2f26a: set_dev_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_dev_info(const struct device *dev, struct dev_printk_info *dev_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b868b0)
Location: drivers/base/core.c:4814
Inline: False
Direct callers:
  - drivers/base/core.c:dev_printk_emit
```
**Symbols:**

```
ffffffff81b868b0-ffffffff81b86a6a: set_dev_info (STB_LOCAL)
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
