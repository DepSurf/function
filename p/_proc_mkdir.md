# Function: <code>_proc_mkdir</code>

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
struct proc_dir_entry *_proc_mkdir(const char *name, umode_t mode, struct proc_dir_entry *parent, void *data, bool force_lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2aaa)
Location: fs/proc/generic.c:484
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/core.c:netfilter_net_init
```
**Symbols:**

```
ffffffff813d2980-ffffffff813d29fa: _proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *_proc_mkdir(const char *name, umode_t mode, struct proc_dir_entry *parent, void *data, bool force_lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d993a)
Location: fs/proc/generic.c:479
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/core.c:netfilter_net_init
```
**Symbols:**

```
ffffffff813d9810-ffffffff813d988a: _proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *_proc_mkdir(const char *name, umode_t mode, struct proc_dir_entry *parent, void *data, bool force_lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b06a)
Location: fs/proc/generic.c:479
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/core.c:netfilter_net_init
```
**Symbols:**

```
ffffffff8142af40-ffffffff8142afba: _proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *_proc_mkdir(const char *name, umode_t mode, struct proc_dir_entry *parent, void *data, bool force_lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a46da)
Location: fs/proc/generic.c:482
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/core.c:netfilter_net_init
```
**Symbols:**

```
ffffffff814a4590-ffffffff814a4619: _proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *_proc_mkdir(const char *name, umode_t mode, struct proc_dir_entry *parent, void *data, bool force_lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539b7a)
Location: fs/proc/generic.c:482
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/core.c:netfilter_net_init
```
**Symbols:**

```
ffffffff81539a10-ffffffff81539a99: _proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *_proc_mkdir(const char *name, umode_t mode, struct proc_dir_entry *parent, void *data, bool force_lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571e1a)
Location: fs/proc/generic.c:481
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/core.c:netfilter_net_init
```
**Symbols:**

```
ffffffff81571cb0-ffffffff81571d39: _proc_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *_proc_mkdir(const char *name, umode_t mode, struct proc_dir_entry *parent, void *data, bool force_lookup);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa7ca)
Location: fs/proc/generic.c:481
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
Direct callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - net/netfilter/core.c:netfilter_net_init
```
**Symbols:**

```
ffffffff815aa660-ffffffff815aa6e9: _proc_mkdir (STB_GLOBAL)
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
