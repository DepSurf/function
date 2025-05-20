# Function: <code>init_tracer_tracefs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81152840)
Location: kernel/trace/trace.c:6753
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff81152840-ffffffff81152d90: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115ba50)
Location: kernel/trace/trace.c:7159
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8115ba50-ffffffff8115bfb0: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81166260)
Location: kernel/trace/trace.c:7442
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81166260-ffffffff811667e0: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81169750)
Location: kernel/trace/trace.c:7811
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81169750-ffffffff81169cce: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81176700)
Location: kernel/trace/trace.c:7822
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81176700-ffffffff81176c49: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:7913
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811858a0-ffffffff81185e3b: init_tracer_tracefs (STB_LOCAL)
ffffffff8118656c-ffffffff81186581: init_tracer_tracefs.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:7982
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811931d0-ffffffff81193793: init_tracer_tracefs (STB_LOCAL)
ffffffff81193efc-ffffffff81193f11: init_tracer_tracefs.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8492
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a0cc0-ffffffff811a1287: init_tracer_tracefs (STB_LOCAL)
ffffffff811a1bba-ffffffff811a1bcf: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811ac6f0-ffffffff811acccf: init_tracer_tracefs (STB_LOCAL)
ffffffff811ad590-ffffffff811ad5a5: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8827
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811be9f0-ffffffff811bee71: init_tracer_tracefs (STB_LOCAL)
ffffffff811c52db-ffffffff811c54cf: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8932
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create_dir
```
**Symbols:**

```
ffffffff811bc5d0-ffffffff811bca5d: init_tracer_tracefs (STB_LOCAL)
ffffffff81be5617-ffffffff81be580b: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9271
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff811bc0c0-ffffffff811bc54d: init_tracer_tracefs (STB_LOCAL)
ffffffff81bd74c5-ffffffff81bd76b9: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9435
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff811e6830-ffffffff811e6fa5: init_tracer_tracefs (STB_LOCAL)
ffffffff81cb4ed2-ffffffff81cb51f1: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9468
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
```
**Symbols:**

```
ffffffff8121e6e0-ffffffff8121eef1: init_tracer_tracefs (STB_LOCAL)
ffffffff81e65f5d-ffffffff81e6628d: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9559
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
```
**Symbols:**

```
ffffffff81268e40-ffffffff81269905: init_tracer_tracefs (STB_LOCAL)
ffffffff8205d4d6-ffffffff8205d521: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9724
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
```
**Symbols:**

```
ffffffff8127ffd0-ffffffff81280a99: init_tracer_tracefs (STB_LOCAL)
ffffffff820dbe8c-ffffffff820dbeda: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9921
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
```
**Symbols:**

```
ffffffff8129a1d0-ffffffff8129ac8b: init_tracer_tracefs (STB_LOCAL)
ffffffff821b7cd6-ffffffff821b7d24: init_tracer_tracefs.cold (STB_LOCAL)
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
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff8000102296f8)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffff8000102296f8-ffff800010229d00: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0466d24)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c0466d24-c04673a0: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b0dd0)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c0000000002b0dd0-c0000000002b1530: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000183dc2)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffe000183dc2-ffffffe000184394: init_tracer_tracefs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a4d10-ffffffff811a52ef: init_tracer_tracefs (STB_LOCAL)
ffffffff811a5bb0-ffffffff811a5bc5: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff81197cc0-ffffffff8119829f: init_tracer_tracefs (STB_LOCAL)
ffffffff81198b40-ffffffff81198b55: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a2ae0-ffffffff811a30bf: init_tracer_tracefs (STB_LOCAL)
ffffffff811a3980-ffffffff811a3995: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void init_tracer_tracefs(struct trace_array *tr, struct dentry *d_tracer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8543
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811b0870-ffffffff811b0e4f: init_tracer_tracefs (STB_LOCAL)
ffffffff811b1710-ffffffff811b1725: init_tracer_tracefs.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
