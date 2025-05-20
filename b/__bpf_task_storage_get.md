# Function: <code>__bpf_task_storage_get</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *__bpf_task_storage_get(struct bpf_map *map, struct task_struct *task, void *value, u64 flags, gfp_t gfp_flags, bool nobusy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81306a00)
Location: kernel/bpf/bpf_task_storage.c:214
Inline: True
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
```
**Symbols:**

```
ffffffff81306a00-ffffffff81306ac4: __bpf_task_storage_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *__bpf_task_storage_get(struct bpf_map *map, struct task_struct *task, void *value, u64 flags, gfp_t gfp_flags, bool nobusy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81335970)
Location: kernel/bpf/bpf_task_storage.c:207
Inline: True
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
```
**Symbols:**

```
ffffffff81335970-ffffffff81335a34: __bpf_task_storage_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *__bpf_task_storage_get(struct bpf_map *map, struct task_struct *task, void *value, u64 flags, gfp_t gfp_flags, bool nobusy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81359fd0)
Location: kernel/bpf/bpf_task_storage.c:207
Inline: True
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
```
**Symbols:**

```
ffffffff81359fd0-ffffffff8135a094: __bpf_task_storage_get (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
