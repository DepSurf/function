# Function: <code>node_read_cpumap</code>

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
In drivers/base/node.c (ffffffff81560714)
Location: drivers/base/node.c:28
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In drivers/base/node.c (ffffffff815b4e74)
Location: drivers/base/node.c:28
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In drivers/base/node.c (ffffffff815e4121)
Location: drivers/base/node.c:28
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In drivers/base/node.c (ffffffff815f8d31)
Location: drivers/base/node.c:28
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81660e40)
Location: drivers/base/node.c:29
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff81660e40-ffffffff81660eeb: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8169c600)
Location: drivers/base/node.c:29
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff8169c600-ffffffff8169c6ab: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bcf90)
Location: drivers/base/node.c:29
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff816bcf90-ffffffff816bd03b: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816f77c0)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff816f77c0-ffffffff816f786a: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8171bc20)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff8171bc20-ffffffff8171bcca: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d7c70)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff817d7c70-ffffffff817d7d1a: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817ec680)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:cpulist_show
  - drivers/base/node.c:cpumap_show
```
**Symbols:**

```
ffffffff817ec680-ffffffff817ec72a: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d0ef0)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:cpulist_show
  - drivers/base/node.c:cpumap_show
```
**Symbols:**

```
ffffffff817d0ef0-ffffffff817d0f9a: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/base/node.c (ffff80001090f59c)
Location: drivers/base/node.c:30
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (c0000000009b0360)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
c0000000009b0360-c0000000009b0434: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816e1f50)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff816e1f50-ffffffff816e1ffa: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bc590)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff816bc590-ffffffff816bc63a: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8170f480)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff8170f480-ffffffff8170f52a: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t node_read_cpumap(struct device *dev, bool list, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8172a240)
Location: drivers/base/node.c:30
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff8172a240-ffffffff8172a2ea: node_read_cpumap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
