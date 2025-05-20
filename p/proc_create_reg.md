# Function: <code>proc_create_reg</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320930)
Location: fs/proc/generic.c:514
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81320930-ffffffff813209b7: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337a30)
Location: fs/proc/generic.c:516
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81337a30-ffffffff81337ab7: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135fbb0)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff8135fbb0-ffffffff8135fc2d: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377e10)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81377e10-ffffffff81377e8d: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0d30)
Location: fs/proc/generic.c:523
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813c0d30-ffffffff813c0db3: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2c20)
Location: fs/proc/generic.c:543
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813d2c20-ffffffff813d2ca3: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9ab0)
Location: fs/proc/generic.c:538
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813d9ab0-ffffffff813d9b33: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b1e0)
Location: fs/proc/generic.c:538
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff8142b1e0-ffffffff8142b263: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4870)
Location: fs/proc/generic.c:541
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff814a4870-ffffffff814a490c: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539d40)
Location: fs/proc/generic.c:541
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81539d40-ffffffff81539ddc: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571fe0)
Location: fs/proc/generic.c:540
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81571fe0-ffffffff81572078: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa990)
Location: fs/proc/generic.c:540
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff815aa990-ffffffff815aaa28: proc_create_reg (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443c88)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffff800010443c88-ffff800010443d38: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608e8c)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
c0608e8c-c0608f58: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0000000005593d0)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/generic.c:proc_create_data
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
c0000000005593d0-c0000000005594b4: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da726)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffe0002da726-ffffffe0002da7ae: proc_create_reg (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813703f0)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813703f0-ffffffff8137046d: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360e80)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff81360e80-ffffffff81360efd: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136dec0)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff8136dec0-ffffffff8136df3d: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_reg(const char *name, umode_t mode, struct proc_dir_entry **parent, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813817f0)
Location: fs/proc/generic.c:517
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_single_data
  - fs/proc/generic.c:proc_create_seq_private
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
**Symbols:**

```
ffffffff813817f0-ffffffff8138186d: proc_create_reg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
