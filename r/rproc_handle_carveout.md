# Function: <code>rproc_handle_carveout</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:871
Inline: False
```
**Symbols:**

```
ffffffff818f4430-ffffffff818f4574: rproc_handle_carveout (STB_LOCAL)
ffffffff818f5670-ffffffff818f56d4: rproc_handle_carveout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:882
Inline: False
```
**Symbols:**

```
ffffffff819ca5f0-ffffffff819ca72d: rproc_handle_carveout (STB_LOCAL)
ffffffff819cbee9-ffffffff819cbf4d: rproc_handle_carveout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:915
Inline: False
```
**Symbols:**

```
ffffffff819c9a70-ffffffff819c9bad: rproc_handle_carveout (STB_LOCAL)
ffffffff81c2e656-ffffffff81c2e6ba: rproc_handle_carveout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:921
Inline: False
```
**Symbols:**

```
ffffffff819aea80-ffffffff819aebbd: rproc_handle_carveout (STB_LOCAL)
ffffffff81c206e9-ffffffff81c2074d: rproc_handle_carveout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:933
Inline: False
```
**Symbols:**

```
ffffffff81a5d050-ffffffff81a5d18a: rproc_handle_carveout (STB_LOCAL)
ffffffff81d3204a-ffffffff81d320ae: rproc_handle_carveout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:929
Inline: False
```
**Symbols:**

```
ffffffff81bcd140-ffffffff81bcd290: rproc_handle_carveout (STB_LOCAL)
ffffffff81efe570-ffffffff81efe5c6: rproc_handle_carveout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d78a20)
Location: drivers/remoteproc/remoteproc_core.c:822
Inline: False
```
**Symbols:**

```
ffffffff81d78a20-ffffffff81d78bb9: rproc_handle_carveout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6970)
Location: drivers/remoteproc/remoteproc_core.c:823
Inline: False
```
**Symbols:**

```
ffffffff81de6970-ffffffff81de6b09: rproc_handle_carveout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9cb50)
Location: drivers/remoteproc/remoteproc_core.c:823
Inline: False
```
**Symbols:**

```
ffffffff81e9cb50-ffffffff81e9cce9: rproc_handle_carveout (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80518)
Location: drivers/remoteproc/remoteproc_core.c:871
Inline: False
```
**Symbols:**

```
ffff800010b80518-ffff800010b806d0: rproc_handle_carveout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c63b0c)
Location: drivers/remoteproc/remoteproc_core.c:871
Inline: False
```
**Symbols:**

```
c0c63b0c-c0c63cc4: rproc_handle_carveout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5ccb0)
Location: drivers/remoteproc/remoteproc_core.c:871
Inline: False
```
**Symbols:**

```
c000000000c5ccb0-c000000000c5ceb0: rproc_handle_carveout (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:871
Inline: False
```
**Symbols:**

```
ffffffff81895760-ffffffff818958a4: rproc_handle_carveout (STB_LOCAL)
ffffffff818969a0-ffffffff81896a04: rproc_handle_carveout.cold (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rproc_handle_carveout(struct rproc *rproc, struct fw_rsc_carveout *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:871
Inline: False
```
**Symbols:**

```
ffffffff81905ec0-ffffffff81906004: rproc_handle_carveout (STB_LOCAL)
ffffffff81907100-ffffffff81907164: rproc_handle_carveout.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *ptr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fw_rsc_carveout *rsc</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
