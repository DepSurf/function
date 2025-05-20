# Function: <code>bpf_pid_task_storage_lookup_elem</code>

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
void *bpf_pid_task_storage_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81221a70)
Location: kernel/bpf/bpf_task_storage.c:103
Inline: False
```
**Symbols:**

```
ffffffff81221a70-ffffffff81221b41: bpf_pid_task_storage_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_pid_task_storage_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81225c90)
Location: kernel/bpf/bpf_task_storage.c:116
Inline: False
```
**Symbols:**

```
ffffffff81225c90-ffffffff81225d75: bpf_pid_task_storage_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_pid_task_storage_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff8125dcb0)
Location: kernel/bpf/bpf_task_storage.c:116
Inline: False
```
**Symbols:**

```
ffffffff8125dcb0-ffffffff8125dd95: bpf_pid_task_storage_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_pid_task_storage_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff812a8050)
Location: kernel/bpf/bpf_task_storage.c:118
Inline: False
```
**Symbols:**

```
ffffffff812a8050-ffffffff812a813f: bpf_pid_task_storage_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_pid_task_storage_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81306890)
Location: kernel/bpf/bpf_task_storage.c:97
Inline: False
```
**Symbols:**

```
ffffffff81306890-ffffffff8130697f: bpf_pid_task_storage_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_pid_task_storage_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff813357f0)
Location: kernel/bpf/bpf_task_storage.c:90
Inline: False
```
**Symbols:**

```
ffffffff813357f0-ffffffff813358df: bpf_pid_task_storage_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_pid_task_storage_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81359e50)
Location: kernel/bpf/bpf_task_storage.c:90
Inline: False
```
**Symbols:**

```
ffffffff81359e50-ffffffff81359f3f: bpf_pid_task_storage_lookup_elem (STB_LOCAL)
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
