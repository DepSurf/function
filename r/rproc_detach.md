# Function: <code>rproc_detach</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_detach(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:2103
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write
```
**Symbols:**

```
ffffffff81c20e57-ffffffff81c20ec7: rproc_detach.cold (STB_LOCAL)
ffffffff819af810-ffffffff819af98a: rproc_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_detach(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:2123
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write
```
**Symbols:**

```
ffffffff81d321bf-ffffffff81d3222f: rproc_detach.cold (STB_LOCAL)
ffffffff81a5dc90-ffffffff81a5de0a: rproc_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_detach(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:2128
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write
```
**Symbols:**

```
ffffffff81efe6ca-ffffffff81efe6fd: rproc_detach.cold (STB_LOCAL)
ffffffff81bcde10-ffffffff81bcdfd2: rproc_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_detach(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d77c20)
Location: drivers/remoteproc/remoteproc_core.c:2052
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write
```
**Symbols:**

```
ffffffff81d77c20-ffffffff81d77d2a: rproc_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_detach(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5b70)
Location: drivers/remoteproc/remoteproc_core.c:2053
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write
```
**Symbols:**

```
ffffffff81de5b70-ffffffff81de5c7a: rproc_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_detach(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9bd50)
Location: drivers/remoteproc/remoteproc_core.c:2053
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_sysfs.c:state_store
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release
  - drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write
```
**Symbols:**

```
ffffffff81e9bd50-ffffffff81e9be5a: rproc_detach (STB_GLOBAL)
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
