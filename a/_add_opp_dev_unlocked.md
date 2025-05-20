# Function: <code>_add_opp_dev_unlocked</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849a92)
Location: drivers/opp/core.c:792
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
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
In drivers/opp/core.c (ffffffff8188c862)
Location: drivers/opp/core.c:870
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
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
In drivers/opp/core.c (ffffffff818be9d2)
Location: drivers/opp/core.c:918
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198fe22)
Location: drivers/opp/core.c:996
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct opp_device *_add_opp_dev_unlocked(const struct device *dev, struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18088)
Location: drivers/opp/core.c:918
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_add_opp_dev
```
**Symbols:**

```
ffff800010b18088-ffff800010b180f8: _add_opp_dev_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct opp_device *_add_opp_dev_unlocked(const struct device *dev, struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf30c0)
Location: drivers/opp/core.c:918
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_add_opp_dev
```
**Symbols:**

```
c0bf30c0-c0bf3124: _add_opp_dev_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct opp_device *_add_opp_dev_unlocked(const struct device *dev, struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a090)
Location: drivers/opp/core.c:918
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_add_opp_dev
```
**Symbols:**

```
c000000000c0a090-c000000000c0a12c: _add_opp_dev_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct opp_device *_add_opp_dev_unlocked(const struct device *dev, struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000700e7e)
Location: drivers/opp/core.c:918
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_add_opp_dev
```
**Symbols:**

```
ffffffe000700e7e-ffffffe000700ee8: _add_opp_dev_unlocked (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff818630f2)
Location: drivers/opp/core.c:918
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
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
In drivers/opp/core.c (ffffffff8182bda2)
Location: drivers/opp/core.c:918
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
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
In drivers/opp/core.c (ffffffff818b3e82)
Location: drivers/opp/core.c:918
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
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
In drivers/opp/core.c (ffffffff818d0132)
Location: drivers/opp/core.c:918
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_dev
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
