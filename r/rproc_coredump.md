# Function: <code>rproc_coredump</code>

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
In drivers/remoteproc/remoteproc_core.c (ffffffff818f5d6b)
Location: drivers/remoteproc/remoteproc_core.c:1565
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb23b)
Location: drivers/remoteproc/remoteproc_core.c:1616
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
```
**Symbols:**

```
ffffffff819cb23b-ffffffff819cb506: rproc_coredump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:230
Inline: False
```
**Symbols:**

```
ffffffff81c2ed14-ffffffff81c2ed29: rproc_coredump.cold (STB_LOCAL)
ffffffff819cb320-ffffffff819cb6ec: rproc_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:234
Inline: False
```
**Symbols:**

```
ffffffff81c20fea-ffffffff81c20fff: rproc_coredump.cold (STB_LOCAL)
ffffffff819b04d0-ffffffff819b089b: rproc_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:234
Inline: False
```
**Symbols:**

```
ffffffff81d329b0-ffffffff81d329c5: rproc_coredump.cold (STB_LOCAL)
ffffffff81a5eb40-ffffffff81a5ef0b: rproc_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:234
Inline: False
```
**Symbols:**

```
ffffffff81efee96-ffffffff81efeeab: rproc_coredump.cold (STB_LOCAL)
ffffffff81bcee00-ffffffff81bcf1db: rproc_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d79de0)
Location: drivers/remoteproc/remoteproc_coredump.c:234
Inline: False
```
**Symbols:**

```
ffffffff81d79de0-ffffffff81d7a1e1: rproc_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de7e40)
Location: drivers/remoteproc/remoteproc_coredump.c:234
Inline: False
```
**Symbols:**

```
ffffffff81de7e40-ffffffff81de82f6: rproc_coredump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rproc_coredump(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9e080)
Location: drivers/remoteproc/remoteproc_coredump.c:235
Inline: False
```
**Symbols:**

```
ffffffff81e9e080-ffffffff81e9e536: rproc_coredump (STB_GLOBAL)
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b81cf8)
Location: drivers/remoteproc/remoteproc_core.c:1565
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
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
In drivers/remoteproc/remoteproc_core.c (c0c651ec)
Location: drivers/remoteproc/remoteproc_core.c:1565
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5ea88)
Location: drivers/remoteproc/remoteproc_core.c:1565
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
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
In drivers/remoteproc/remoteproc_core.c (ffffffff8189709b)
Location: drivers/remoteproc/remoteproc_core.c:1565
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819077fb)
Location: drivers/remoteproc/remoteproc_core.c:1565
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
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
