# Function: <code>icc_summary_show</code>

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
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dbe00)
Location: drivers/interconnect/core.c:41
Inline: False
```
**Symbols:**

```
ffffffff819dbe00-ffffffff819dbf07: icc_summary_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819db460)
Location: drivers/interconnect/core.c:43
Inline: False
```
**Symbols:**

```
ffffffff819db460-ffffffff819db567: icc_summary_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c1710)
Location: drivers/interconnect/core.c:43
Inline: False
```
**Symbols:**

```
ffffffff819c1710-ffffffff819c1817: icc_summary_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:43
Inline: False
```
**Symbols:**

```
ffffffff81a70f70-ffffffff81a71093: icc_summary_show (STB_LOCAL)
ffffffff81d3484d-ffffffff81d3486c: icc_summary_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:43
Inline: False
```
**Symbols:**

```
ffffffff81be2650-ffffffff81be2785: icc_summary_show (STB_LOCAL)
ffffffff81f00ca3-ffffffff81f00cc2: icc_summary_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:43
Inline: False
```
**Symbols:**

```
ffffffff81d8e150-ffffffff81d8e285: icc_summary_show (STB_LOCAL)
ffffffff820aaa46-ffffffff820aaa65: icc_summary_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:42
Inline: False
```
**Symbols:**

```
ffffffff81dfca30-ffffffff81dfcb65: icc_summary_show (STB_LOCAL)
ffffffff8212bf82-ffffffff8212bfa1: icc_summary_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int icc_summary_show(struct seq_file *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:43
Inline: False
```
**Symbols:**

```
ffffffff81eb3480-ffffffff81eb35b5: icc_summary_show (STB_LOCAL)
ffffffff8220dc34-ffffffff8220dc53: icc_summary_show.cold (STB_LOCAL)
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
