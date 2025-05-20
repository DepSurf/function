# Function: <code>rproc_start_subdevices</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f5349)
Location: drivers/remoteproc/remoteproc_core.c:1117
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb17c)
Location: drivers/remoteproc/remoteproc_core.c:1128
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rproc_start_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2dd18)
Location: drivers/remoteproc/remoteproc_core.c:1186
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81c2dd18-ffffffff81c2dd88: rproc_start_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rproc_start_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c1fec8)
Location: drivers/remoteproc/remoteproc_core.c:1192
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81c1fec8-ffffffff81c1ff38: rproc_start_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rproc_start_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d3182a)
Location: drivers/remoteproc/remoteproc_core.c:1208
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81d3182a-ffffffff81d3189a: rproc_start_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rproc_start_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efdcf9)
Location: drivers/remoteproc/remoteproc_core.c:1204
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81efdcf9-ffffffff81efdd71: rproc_start_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_start_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d75a50)
Location: drivers/remoteproc/remoteproc_core.c:1097
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81d75a50-ffffffff81d75ae0: rproc_start_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_start_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de3990)
Location: drivers/remoteproc/remoteproc_core.c:1098
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81de3990-ffffffff81de3a20: rproc_start_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_start_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e99a80)
Location: drivers/remoteproc/remoteproc_core.c:1098
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81e99a80-ffffffff81e99b10: rproc_start_subdevices (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b815f4)
Location: drivers/remoteproc/remoteproc_core.c:1117
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
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
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1117
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5e1dc)
Location: drivers/remoteproc/remoteproc_core.c:1117
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81896679)
Location: drivers/remoteproc/remoteproc_core.c:1117
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906dd9)
Location: drivers/remoteproc/remoteproc_core.c:1117
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
</details>
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
