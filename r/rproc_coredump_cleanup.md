# Function: <code>rproc_coredump_cleanup</code>

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
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4ded)
Location: drivers/remoteproc/remoteproc_core.c:1235
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9d84)
Location: drivers/remoteproc/remoteproc_core.c:1246
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819cb2b0)
Location: drivers/remoteproc/remoteproc_coredump.c:26
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff819cb2b0-ffffffff819cb318: rproc_coredump_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819b0460)
Location: drivers/remoteproc/remoteproc_coredump.c:26
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff819b0460-ffffffff819b04c8: rproc_coredump_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5ead0)
Location: drivers/remoteproc/remoteproc_coredump.c:26
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81a5ead0-ffffffff81a5eb38: rproc_coredump_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bced90)
Location: drivers/remoteproc/remoteproc_coredump.c:26
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81bced90-ffffffff81bcee00: rproc_coredump_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d79d60)
Location: drivers/remoteproc/remoteproc_coredump.c:26
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81d79d60-ffffffff81d79dd0: rproc_coredump_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de7dc0)
Location: drivers/remoteproc/remoteproc_coredump.c:26
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81de7dc0-ffffffff81de7e30: rproc_coredump_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rproc_coredump_cleanup(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9d410)
Location: drivers/remoteproc/remoteproc_coredump.c:26
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81e9d410-ffffffff81e9d480: rproc_coredump_cleanup (STB_GLOBAL)
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b80f78)
Location: drivers/remoteproc/remoteproc_core.c:1235
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
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
In drivers/remoteproc/remoteproc_core.c (c0c645a8)
Location: drivers/remoteproc/remoteproc_core.c:1235
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5da00)
Location: drivers/remoteproc/remoteproc_core.c:1235
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
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
In drivers/remoteproc/remoteproc_core.c (ffffffff8189611d)
Location: drivers/remoteproc/remoteproc_core.c:1235
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
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
In drivers/remoteproc/remoteproc_core.c (ffffffff8190687d)
Location: drivers/remoteproc/remoteproc_core.c:1235
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
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
