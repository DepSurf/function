# Function: <code>rproc_create_trace_file</code>

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
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:319
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff818f6951-ffffffff818f696e: rproc_create_trace_file.cold (STB_LOCAL)
ffffffff818f67d0-ffffffff818f680c: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:299
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff819cca83-ffffffff819ccaa0: rproc_create_trace_file.cold (STB_LOCAL)
ffffffff819cc900-ffffffff819cc93b: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:386
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81c2ed85-ffffffff81c2eda2: rproc_create_trace_file.cold (STB_LOCAL)
ffffffff819cc0d0-ffffffff819cc10b: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:386
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81c2105b-ffffffff81c21078: rproc_create_trace_file.cold (STB_LOCAL)
ffffffff819b1240-ffffffff819b127b: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:386
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81d32a36-ffffffff81d32a53: rproc_create_trace_file.cold (STB_LOCAL)
ffffffff81a5f920-ffffffff81a5f95b: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81bcfcc0)
Location: drivers/remoteproc/remoteproc_debugfs.c:386
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81bcfcc0-ffffffff81bcfcf5: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81d7adf0)
Location: drivers/remoteproc/remoteproc_debugfs.c:386
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81d7adf0-ffffffff81d7ae25: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81de8fb0)
Location: drivers/remoteproc/remoteproc_debugfs.c:386
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81de8fb0-ffffffff81de8fe5: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81e9f1f0)
Location: drivers/remoteproc/remoteproc_debugfs.c:386
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81e9f1f0-ffffffff81e9f225: rproc_create_trace_file (STB_GLOBAL)
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
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffff800010b82978)
Location: drivers/remoteproc/remoteproc_debugfs.c:319
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffff800010b82978-ffff800010b829ec: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (c0c65d38)
Location: drivers/remoteproc/remoteproc_debugfs.c:319
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
c0c65d38-c0c65d98: rproc_create_trace_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (c000000000c5fa20)
Location: drivers/remoteproc/remoteproc_debugfs.c:319
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
c000000000c5fa20-c000000000c5faa0: rproc_create_trace_file (STB_GLOBAL)
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
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:319
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff81897c81-ffffffff81897c9e: rproc_create_trace_file.cold (STB_LOCAL)
ffffffff81897b00-ffffffff81897b3c: rproc_create_trace_file (STB_GLOBAL)
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
struct dentry *rproc_create_trace_file(const char *name, struct rproc *rproc, struct rproc_debug_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:319
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
**Symbols:**

```
ffffffff819083e1-ffffffff819083fe: rproc_create_trace_file.cold (STB_LOCAL)
ffffffff81908260-ffffffff8190829c: rproc_create_trace_file (STB_GLOBAL)
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
