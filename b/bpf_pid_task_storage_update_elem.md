# Function: <code>bpf_pid_task_storage_update_elem</code>

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
int bpf_pid_task_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81221820)
Location: kernel/bpf/bpf_task_storage.c:134
Inline: False
```
**Symbols:**

```
ffffffff81221820-ffffffff812218e9: bpf_pid_task_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_pid_task_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81225bc0)
Location: kernel/bpf/bpf_task_storage.c:149
Inline: False
```
**Symbols:**

```
ffffffff81225bc0-ffffffff81225c8c: bpf_pid_task_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_pid_task_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff8125dbe0)
Location: kernel/bpf/bpf_task_storage.c:149
Inline: False
```
**Symbols:**

```
ffffffff8125dbe0-ffffffff8125dcac: bpf_pid_task_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_pid_task_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff812a7f60)
Location: kernel/bpf/bpf_task_storage.c:151
Inline: False
```
**Symbols:**

```
ffffffff812a7f60-ffffffff812a8044: bpf_pid_task_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_pid_task_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81306790)
Location: kernel/bpf/bpf_task_storage.c:130
Inline: False
```
**Symbols:**

```
ffffffff81306790-ffffffff81306874: bpf_pid_task_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int bpf_pid_task_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff813356f0)
Location: kernel/bpf/bpf_task_storage.c:123
Inline: False
```
**Symbols:**

```
ffffffff813356f0-ffffffff813357d5: bpf_pid_task_storage_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int bpf_pid_task_storage_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81359d50)
Location: kernel/bpf/bpf_task_storage.c:123
Inline: False
```
**Symbols:**

```
ffffffff81359d50-ffffffff81359e35: bpf_pid_task_storage_update_elem (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
