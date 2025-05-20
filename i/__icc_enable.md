# Function: <code>__icc_enable</code>

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
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dcdc0)
Location: drivers/interconnect/core.c:644
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff819dcdc0-ffffffff819dce47: __icc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dc4e0)
Location: drivers/interconnect/core.c:675
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff819dc4e0-ffffffff819dc567: __icc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c2760)
Location: drivers/interconnect/core.c:675
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff819c2760-ffffffff819c27e7: __icc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a72010)
Location: drivers/interconnect/core.c:675
Inline: True
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff81a72010-ffffffff81a72097: __icc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be3ae0)
Location: drivers/interconnect/core.c:675
Inline: True
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff81be3ae0-ffffffff81be3b8e: __icc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8f7e0)
Location: drivers/interconnect/core.c:675
Inline: True
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff81d8f7e0-ffffffff81d8f88e: __icc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfddc0)
Location: drivers/interconnect/core.c:674
Inline: True
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff81dfddc0-ffffffff81dfde6e: __icc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __icc_enable(struct icc_path *path, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb4820)
Location: drivers/interconnect/core.c:741
Inline: True
Direct callers:
  - drivers/interconnect/core.c:icc_disable
  - drivers/interconnect/core.c:icc_enable
```
**Symbols:**

```
ffffffff81eb4820-ffffffff81eb48ce: __icc_enable (STB_LOCAL)
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
