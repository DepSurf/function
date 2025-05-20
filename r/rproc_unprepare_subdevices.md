# Function: <code>rproc_unprepare_subdevices</code>

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
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3d96)
Location: drivers/remoteproc/remoteproc_core.c:1151
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rproc_unprepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c96e6)
Location: drivers/remoteproc/remoteproc_core.c:1162
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff819cafc8-ffffffff819cb005: rproc_unprepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rproc_unprepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9396)
Location: drivers/remoteproc/remoteproc_core.c:1220
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81c2dd88-ffffffff81c2ddc5: rproc_unprepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rproc_unprepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ada60)
Location: drivers/remoteproc/remoteproc_core.c:1226
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff819ada60-ffffffff819ada9e: rproc_unprepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rproc_unprepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5bfc0)
Location: drivers/remoteproc/remoteproc_core.c:1242
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81a5bfc0-ffffffff81a5bffe: rproc_unprepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rproc_unprepare_subdevices(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcbf10)
Location: drivers/remoteproc/remoteproc_core.c:1238
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
**Symbols:**

```
ffffffff81bcbf10-ffffffff81bcbf56: rproc_unprepare_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d77b51)
Location: drivers/remoteproc/remoteproc_core.c:1131
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5aa1)
Location: drivers/remoteproc/remoteproc_core.c:1132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9bc81)
Location: drivers/remoteproc/remoteproc_core.c:1132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:__rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_start
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b7fbd0)
Location: drivers/remoteproc/remoteproc_core.c:1151
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (c0c63324)
Location: drivers/remoteproc/remoteproc_core.c:1151
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5b768)
Location: drivers/remoteproc/remoteproc_core.c:1151
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffffffff818950c6)
Location: drivers/remoteproc/remoteproc_core.c:1151
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81905826)
Location: drivers/remoteproc/remoteproc_core.c:1151
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_start
```
</details>
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
</ul>
