# Function: <code>task_storage_ptr</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **task_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81221981)
Location: kernel/bpf/bpf_task_storage.c:24
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
**Symbols:**

```
ffffffff812217f0-ffffffff81221811: task_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_local_storage **task_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81225ac0)
Location: kernel/bpf/bpf_task_storage.c:48
Inline: False
```
**Symbols:**

```
ffffffff81225ac0-ffffffff81225ad2: task_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_local_storage **task_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff8125dae0)
Location: kernel/bpf/bpf_task_storage.c:48
Inline: False
```
**Symbols:**

```
ffffffff8125dae0-ffffffff8125daf2: task_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_local_storage **task_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff812a7e30)
Location: kernel/bpf/bpf_task_storage.c:49
Inline: False
```
**Symbols:**

```
ffffffff812a7e30-ffffffff812a7e48: task_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_local_storage **task_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81306630)
Location: kernel/bpf/bpf_task_storage.c:49
Inline: False
```
**Symbols:**

```
ffffffff81306630-ffffffff81306648: task_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_local_storage **task_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff813355a0)
Location: kernel/bpf/bpf_task_storage.c:49
Inline: False
```
**Symbols:**

```
ffffffff813355a0-ffffffff813355b8: task_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_local_storage **task_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_task_storage.c (ffffffff81359c00)
Location: kernel/bpf/bpf_task_storage.c:49
Inline: False
```
**Symbols:**

```
ffffffff81359c00-ffffffff81359c18: task_storage_ptr (STB_LOCAL)
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
