# Function: <code>bpf_task_storage_unlock</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81225f34)
Location: kernel/bpf/bpf_task_storage.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff8125df54)
Location: kernel/bpf/bpf_task_storage.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff812a8328)
Location: kernel/bpf/bpf_task_storage.c:32
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81306cbe)
Location: kernel/bpf/bpf_task_storage.c:32
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81335c2b)
Location: kernel/bpf/bpf_task_storage.c:32
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff8135a28b)
Location: kernel/bpf/bpf_task_storage.c:32
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
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
