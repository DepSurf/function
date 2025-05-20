# Function: <code>task_storage_map_alloc</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_map *task_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81221920)
Location: kernel/bpf/bpf_task_storage.c:261
Inline: False
```
**Symbols:**

```
ffffffff81221920-ffffffff81221959: task_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_map *task_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81225dc0)
Location: kernel/bpf/bpf_task_storage.c:283
Inline: False
```
**Symbols:**

```
ffffffff81225dc0-ffffffff81225df9: task_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_map *task_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff8125dde0)
Location: kernel/bpf/bpf_task_storage.c:283
Inline: False
```
**Symbols:**

```
ffffffff8125dde0-ffffffff8125de19: task_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_map *task_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff812a8180)
Location: kernel/bpf/bpf_task_storage.c:289
Inline: False
```
**Symbols:**

```
ffffffff812a8180-ffffffff812a81bc: task_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_map *task_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff813069d0)
Location: kernel/bpf/bpf_task_storage.c:317
Inline: False
```
**Symbols:**

```
ffffffff813069d0-ffffffff813069ef: task_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_map *task_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81335930)
Location: kernel/bpf/bpf_task_storage.c:310
Inline: False
```
**Symbols:**

```
ffffffff81335930-ffffffff81335956: task_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_map *task_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81359f90)
Location: kernel/bpf/bpf_task_storage.c:310
Inline: False
```
**Symbols:**

```
ffffffff81359f90-ffffffff81359fb6: task_storage_map_alloc (STB_LOCAL)
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
