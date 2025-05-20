# Function: <code>pressure_write</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120d870)
Location: kernel/cgroup/cgroup.c:3742
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff8120d870-ffffffff8120da27: pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81223260)
Location: kernel/cgroup/cgroup.c:3711
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81223260-ffffffff81223421: pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123af50)
Location: kernel/cgroup/cgroup.c:3773
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff8123af50-ffffffff8123b111: pressure_write (STB_LOCAL)
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
