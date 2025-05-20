# Function: <code>rproc_stop_subdevices</code>

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
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3d2f)
Location: drivers/remoteproc/remoteproc_core.c:1141
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819c967f)
Location: drivers/remoteproc/remoteproc_core.c:1152
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c932f)
Location: drivers/remoteproc/remoteproc_core.c:1210
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rproc_stop_subdevices(struct rproc *rproc, bool crashed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ada10)
Location: drivers/remoteproc/remoteproc_core.c:1216
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
```
**Symbols:**

```
ffffffff819ada10-ffffffff819ada59: rproc_stop_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rproc_stop_subdevices(struct rproc *rproc, bool crashed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5bf70)
Location: drivers/remoteproc/remoteproc_core.c:1232
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
```
**Symbols:**

```
ffffffff81a5bf70-ffffffff81a5bfb9: rproc_stop_subdevices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rproc_stop_subdevices(struct rproc *rproc, bool crashed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcbeb0)
Location: drivers/remoteproc/remoteproc_core.c:1228
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
```
**Symbols:**

```
ffffffff81bcbeb0-ffffffff81bcbf03: rproc_stop_subdevices (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81d77b06)
Location: drivers/remoteproc/remoteproc_core.c:1121
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5a56)
Location: drivers/remoteproc/remoteproc_core.c:1122
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9bc36)
Location: drivers/remoteproc/remoteproc_core.c:1122
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b7fb84)
Location: drivers/remoteproc/remoteproc_core.c:1141
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (c0c632d0)
Location: drivers/remoteproc/remoteproc_core.c:1141
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5b700)
Location: drivers/remoteproc/remoteproc_core.c:1141
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffffffff8189505f)
Location: drivers/remoteproc/remoteproc_core.c:1141
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819057bf)
Location: drivers/remoteproc/remoteproc_core.c:1141
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_stop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
