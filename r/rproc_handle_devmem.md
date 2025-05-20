# Function: <code>rproc_handle_devmem</code>

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
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:677
Inline: False
```
**Symbols:**

```
ffffffff818f3a60-ffffffff818f3b5c: rproc_handle_devmem (STB_LOCAL)
ffffffff818f50f8-ffffffff818f514a: rproc_handle_devmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:686
Inline: False
```
**Symbols:**

```
ffffffff819ca250-ffffffff819ca34c: rproc_handle_devmem (STB_LOCAL)
ffffffff819cbe07-ffffffff819cbe59: rproc_handle_devmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:719
Inline: False
```
**Symbols:**

```
ffffffff819c96d0-ffffffff819c97cc: rproc_handle_devmem (STB_LOCAL)
ffffffff81c2e574-ffffffff81c2e5c6: rproc_handle_devmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:724
Inline: False
```
**Symbols:**

```
ffffffff819ae6e0-ffffffff819ae7dc: rproc_handle_devmem (STB_LOCAL)
ffffffff81c20607-ffffffff81c20659: rproc_handle_devmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:730
Inline: False
```
**Symbols:**

```
ffffffff81a5ccb0-ffffffff81a5cda9: rproc_handle_devmem (STB_LOCAL)
ffffffff81d31f68-ffffffff81d31fba: rproc_handle_devmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:726
Inline: False
```
**Symbols:**

```
ffffffff81bccd20-ffffffff81bcce35: rproc_handle_devmem (STB_LOCAL)
ffffffff81efe497-ffffffff81efe4e0: rproc_handle_devmem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d774b0)
Location: drivers/remoteproc/remoteproc_core.c:619
Inline: False
```
**Symbols:**

```
ffffffff81d774b0-ffffffff81d7762c: rproc_handle_devmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de53f0)
Location: drivers/remoteproc/remoteproc_core.c:619
Inline: False
```
**Symbols:**

```
ffffffff81de53f0-ffffffff81de5572: rproc_handle_devmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, void *ptr, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9b570)
Location: drivers/remoteproc/remoteproc_core.c:619
Inline: False
```
**Symbols:**

```
ffffffff81e9b570-ffffffff81e9b721: rproc_handle_devmem (STB_LOCAL)
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
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f7a8)
Location: drivers/remoteproc/remoteproc_core.c:677
Inline: False
```
**Symbols:**

```
ffff800010b7f7a8-ffff800010b7f900: rproc_handle_devmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c62f10)
Location: drivers/remoteproc/remoteproc_core.c:677
Inline: False
```
**Symbols:**

```
c0c62f10-c0c6306c: rproc_handle_devmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5c000)
Location: drivers/remoteproc/remoteproc_core.c:677
Inline: False
```
**Symbols:**

```
c000000000c5c000-c000000000c5c1b8: rproc_handle_devmem (STB_LOCAL)
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
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:677
Inline: False
```
**Symbols:**

```
ffffffff81894d90-ffffffff81894e8c: rproc_handle_devmem (STB_LOCAL)
ffffffff81896428-ffffffff8189647a: rproc_handle_devmem.cold (STB_LOCAL)
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
int rproc_handle_devmem(struct rproc *rproc, struct fw_rsc_devmem *rsc, int offset, int avail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:677
Inline: False
```
**Symbols:**

```
ffffffff819054f0-ffffffff819055ec: rproc_handle_devmem (STB_LOCAL)
ffffffff81906b88-ffffffff81906bda: rproc_handle_devmem.cold (STB_LOCAL)
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
<code>struct fw_rsc_devmem *rsc</code>
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
