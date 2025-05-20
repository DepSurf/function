# Function: <code>cgroup_pressure_write</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158eb0)
Location: kernel/cgroup/cgroup.c:3623
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81158eb0-ffffffff81158fb8: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164b10)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81164b10-ffffffff81164c18: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175bb0)
Location: kernel/cgroup/cgroup.c:3566
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81175bb0-ffffffff81175cb8: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172860)
Location: kernel/cgroup/cgroup.c:3562
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81172860-ffffffff811729a5: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173450)
Location: kernel/cgroup/cgroup.c:3575
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81173450-ffffffff81173595: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119a3f0)
Location: kernel/cgroup/cgroup.c:3630
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff8119a3f0-ffffffff8119a588: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811ca500)
Location: kernel/cgroup/cgroup.c:3641
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff811ca500-ffffffff811ca6ba: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3824
Inline: False
```
**Symbols:**

```
ffffffff8120d6c0-ffffffff8120d858: cgroup_pressure_write (STB_LOCAL)
ffffffff8205c27f-ffffffff8205c29b: cgroup_pressure_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3793
Inline: False
```
**Symbols:**

```
ffffffff812230b0-ffffffff81223248: cgroup_pressure_write (STB_LOCAL)
ffffffff820daa99-ffffffff820daab5: cgroup_pressure_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3855
Inline: False
```
**Symbols:**

```
ffffffff8123ada0-ffffffff8123af38: cgroup_pressure_write (STB_LOCAL)
ffffffff821b6717-ffffffff821b6733: cgroup_pressure_write.cold (STB_LOCAL)
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
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d64c8)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffff8000101d64c8-ffff8000101d65a8: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0419158)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
c0419158-c0419320: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000242150)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
c000000000242150-c0000000002423b0: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014f6ce)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffe00014f6ce-ffffffe00014f838: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d130)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff8115d130-ffffffff8115d238: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81150420)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81150420-ffffffff81150528: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115af00)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff8115af00-ffffffff8115b008: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t cgroup_pressure_write(struct kernfs_open_file *of, char *buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81167fa0)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_write
```
**Symbols:**

```
ffffffff81167fa0-ffffffff811680e7: cgroup_pressure_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t off</code>
</li>
<li>
<b>Param removed. </b>
<code>enum psi_res res</code>
</li>
</ul>
</details>
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
