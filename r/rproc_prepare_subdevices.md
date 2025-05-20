# Function: <code>rproc_prepare_subdevices</code>

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
In drivers/remoteproc/remoteproc_core.c (ffffffff818f52a4)
Location: drivers/remoteproc/remoteproc_core.c:1093
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb0d6)
Location: drivers/remoteproc/remoteproc_core.c:1104
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
int rproc_prepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2dcad)
Location: drivers/remoteproc/remoteproc_core.c:1162
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81c2dcad-ffffffff81c2dd18: rproc_prepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c1fe5d)
Location: drivers/remoteproc/remoteproc_core.c:1168
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81c1fe5d-ffffffff81c1fec8: rproc_prepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d317bf)
Location: drivers/remoteproc/remoteproc_core.c:1184
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81d317bf-ffffffff81d3182a: rproc_prepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efdc88)
Location: drivers/remoteproc/remoteproc_core.c:1180
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81efdc88-ffffffff81efdcf9: rproc_prepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d759b0)
Location: drivers/remoteproc/remoteproc_core.c:1073
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81d759b0-ffffffff81d75a37: rproc_prepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de38f0)
Location: drivers/remoteproc/remoteproc_core.c:1074
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81de38f0-ffffffff81de3977: rproc_prepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_prepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e999e0)
Location: drivers/remoteproc/remoteproc_core.c:1074
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81e999e0-ffffffff81e99a67: rproc_prepare_subdevices (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b81550)
Location: drivers/remoteproc/remoteproc_core.c:1093
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
In drivers/remoteproc/remoteproc_core.c (c0c64a98)
Location: drivers/remoteproc/remoteproc_core.c:1093
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5e10c)
Location: drivers/remoteproc/remoteproc_core.c:1093
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
In drivers/remoteproc/remoteproc_core.c (ffffffff818965d4)
Location: drivers/remoteproc/remoteproc_core.c:1093
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81906d34)
Location: drivers/remoteproc/remoteproc_core.c:1093
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
