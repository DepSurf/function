# Function: <code>proc_create_net_single_write</code>

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
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81327df0)
Location: fs/proc/proc_net.c:215
Inline: False
```
**Symbols:**

```
ffffffff81327df0-ffffffff81327e43: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8133efe0)
Location: fs/proc/proc_net.c:234
Inline: False
```
**Symbols:**

```
ffffffff8133efe0-ffffffff8133f03b: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81367340)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffffffff81367340-ffffffff8136739b: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8137f5c0)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffffffff8137f5c0-ffffffff8137f61b: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813c9830)
Location: fs/proc/proc_net.c:254
Inline: False
```
**Symbols:**

```
ffffffff813c9830-ffffffff813c988b: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813db4a0)
Location: fs/proc/proc_net.c:238
Inline: False
```
**Symbols:**

```
ffffffff813db4a0-ffffffff813db4fb: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813e23d0)
Location: fs/proc/proc_net.c:238
Inline: False
```
**Symbols:**

```
ffffffff813e23d0-ffffffff813e242b: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81433ee0)
Location: fs/proc/proc_net.c:238
Inline: False
```
**Symbols:**

```
ffffffff81433ee0-ffffffff81433f3b: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814adf30)
Location: fs/proc/proc_net.c:251
Inline: False
```
**Symbols:**

```
ffffffff814adf30-ffffffff814adf9d: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815444d0)
Location: fs/proc/proc_net.c:248
Inline: False
```
**Symbols:**

```
ffffffff815444d0-ffffffff8154453d: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8157c0d0)
Location: fs/proc/proc_net.c:248
Inline: False
```
**Symbols:**

```
ffffffff8157c0d0-ffffffff8157c13d: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815b49e0)
Location: fs/proc/proc_net.c:248
Inline: False
```
**Symbols:**

```
ffffffff815b49e0-ffffffff815b4a4d: proc_create_net_single_write (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffff80001044cd58)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffff80001044cd58-ffff80001044cde4: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c061147c)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
c061147c-c06114e4: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c000000000564390)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
c000000000564390-c000000000564420: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffe0002e1aba)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffffffe0002e1aba-ffffffe0002e1b38: proc_create_net_single_write (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81377ba0)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffffffff81377ba0-ffffffff81377bfb: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81368670)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffffffff81368670-ffffffff813686cb: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81375670)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffffffff81375670-ffffffff813756cb: proc_create_net_single_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_single_write(const char *name, umode_t mode, struct proc_dir_entry *parent, int (*show)(struct seq_file *, void *), proc_write_t write, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81389110)
Location: fs/proc/proc_net.c:235
Inline: False
```
**Symbols:**

```
ffffffff81389110-ffffffff8138916b: proc_create_net_single_write (STB_GLOBAL)
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
