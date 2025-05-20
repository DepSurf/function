# Function: <code>bpf_iter_task</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff82cf7a99)
Location: kernel/bpf/task_iter.c:79
Inline: False
```
**Symbols:**

```
ffffffff82cf7a99-ffffffff82cf7aa6: bpf_iter_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff82fe46a6)
Location: kernel/bpf/task_iter.c:87
Inline: False
```
**Symbols:**

```
ffffffff82fe46a6-ffffffff82fe46b3: bpf_iter_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff831eedab)
Location: kernel/bpf/task_iter.c:87
Inline: False
```
**Symbols:**

```
ffffffff831eedab-ffffffff831eedb8: bpf_iter_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff832d434d)
Location: kernel/bpf/task_iter.c:87
Inline: False
```
**Symbols:**

```
ffffffff832d434d-ffffffff832d435a: bpf_iter_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff834889cc)
Location: kernel/bpf/task_iter.c:88
Inline: False
```
**Symbols:**

```
ffffffff834889cc-ffffffff834889dd: bpf_iter_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff83eb8da0)
Location: kernel/bpf/task_iter.c:194
Inline: False
```
**Symbols:**

```
ffffffff83eb8da0-ffffffff83eb8db1: bpf_iter_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff836de2d0)
Location: kernel/bpf/task_iter.c:194
Inline: False
```
**Symbols:**

```
ffffffff836de2d0-ffffffff836de2e1: bpf_iter_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_task(struct bpf_iter_meta *meta, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff83910910)
Location: kernel/bpf/task_iter.c:174
Inline: False
```
**Symbols:**

```
ffffffff83910910-ffffffff83910921: bpf_iter_task (STB_GLOBAL)
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
