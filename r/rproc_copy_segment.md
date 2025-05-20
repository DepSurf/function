# Function: <code>rproc_copy_segment</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rproc_copy_segment(struct rproc *rproc, void *dest, struct rproc_dump_segment *segment, size_t offset, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819caa95)
Location: drivers/remoteproc/remoteproc_coredump.c:151
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff819caa60-ffffffff819caadd: rproc_copy_segment (STB_LOCAL)
ffffffff81c2ecc6-ffffffff81c2ecf8: rproc_copy_segment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rproc_copy_segment(struct rproc *rproc, void *dest, struct rproc_dump_segment *segment, size_t offset, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819afc48)
Location: drivers/remoteproc/remoteproc_coredump.c:151
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff819afbf0-ffffffff819afc96: rproc_copy_segment (STB_LOCAL)
ffffffff81c20fa3-ffffffff81c20fd5: rproc_copy_segment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rproc_copy_segment(struct rproc *rproc, void *dest, struct rproc_dump_segment *segment, size_t offset, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:151
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81a5e240-ffffffff81a5e30e: rproc_copy_segment (STB_LOCAL)
ffffffff81d3294c-ffffffff81d3299b: rproc_copy_segment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rproc_copy_segment(struct rproc *rproc, void *dest, struct rproc_dump_segment *segment, size_t offset, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:151
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81bce4a0-ffffffff81bce567: rproc_copy_segment (STB_LOCAL)
ffffffff81efee2c-ffffffff81efee81: rproc_copy_segment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rproc_copy_segment(struct rproc *rproc, void *dest, struct rproc_dump_segment *segment, size_t offset, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:151
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81d793c0-ffffffff81d794b8: rproc_copy_segment (STB_LOCAL)
ffffffff820aa2db-ffffffff820aa2ff: rproc_copy_segment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rproc_copy_segment(struct rproc *rproc, void *dest, struct rproc_dump_segment *segment, size_t offset, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:151
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81de7310-ffffffff81de7408: rproc_copy_segment (STB_LOCAL)
ffffffff8212b7da-ffffffff8212b7fe: rproc_copy_segment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rproc_copy_segment(struct rproc *rproc, void *dest, struct rproc_dump_segment *segment, size_t offset, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (0)
Location: drivers/remoteproc/remoteproc_coredump.c:152
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read
```
**Symbols:**

```
ffffffff81e9d570-ffffffff81e9d668: rproc_copy_segment (STB_LOCAL)
ffffffff8220d401-ffffffff8220d425: rproc_copy_segment.cold (STB_LOCAL)
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
