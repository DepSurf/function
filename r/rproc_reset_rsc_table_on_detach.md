# Function: <code>rproc_reset_rsc_table_on_detach</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af882)
Location: drivers/remoteproc/remoteproc_core.c:1590
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5dd02)
Location: drivers/remoteproc/remoteproc_core.c:1606
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcdea3)
Location: drivers/remoteproc/remoteproc_core.c:1602
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_reset_rsc_table_on_detach(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76210)
Location: drivers/remoteproc/remoteproc_core.c:1495
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
```
**Symbols:**

```
ffffffff81d76210-ffffffff81d7629f: rproc_reset_rsc_table_on_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_reset_rsc_table_on_detach(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4150)
Location: drivers/remoteproc/remoteproc_core.c:1496
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
```
**Symbols:**

```
ffffffff81de4150-ffffffff81de41df: rproc_reset_rsc_table_on_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_reset_rsc_table_on_detach(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a240)
Location: drivers/remoteproc/remoteproc_core.c:1496
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:__rproc_detach
```
**Symbols:**

```
ffffffff81e9a240-ffffffff81e9a2cf: rproc_reset_rsc_table_on_detach (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
