# Function: <code>bpf_local_storage_map_alloc</code>

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
struct bpf_local_storage_map *bpf_local_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812303a0)
Location: kernel/bpf/bpf_local_storage.c:543
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff812303a0-ffffffff8123049d: bpf_local_storage_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_local_storage_map *bpf_local_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225980)
Location: kernel/bpf/bpf_local_storage.c:558
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff81225980-ffffffff81225a82: bpf_local_storage_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_map *bpf_local_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:558
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff81cb932b-ffffffff81cb9349: bpf_local_storage_map_alloc.cold (STB_LOCAL)
ffffffff8125d980-ffffffff8125daa4: bpf_local_storage_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_map *bpf_local_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:607
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff81e6a61f-ffffffff81e6a63d: bpf_local_storage_map_alloc.cold (STB_LOCAL)
ffffffff812a7cd0-ffffffff812a7def: bpf_local_storage_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_local_storage_map_alloc(union bpf_attr *attr, struct bpf_local_storage_cache *cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:640
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff82061754-ffffffff82061772: bpf_local_storage_map_alloc.cold (STB_LOCAL)
ffffffff81306350-ffffffff813064f5: bpf_local_storage_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_local_storage_map_alloc(union bpf_attr *attr, struct bpf_local_storage_cache *cache, bool bpf_ma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:811
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff820e0df4-ffffffff820e0e12: bpf_local_storage_map_alloc.cold (STB_LOCAL)
ffffffff81335190-ffffffff8133541a: bpf_local_storage_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_local_storage_map_alloc(union bpf_attr *attr, struct bpf_local_storage_cache *cache, bool bpf_ma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:792
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff821bd5a9-ffffffff821bd5c7: bpf_local_storage_map_alloc.cold (STB_LOCAL)
ffffffff813597f0-ffffffff81359a7a: bpf_local_storage_map_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_local_storage_cache *cache</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct bpf_local_storage_map *</code> ➡️ <code>struct bpf_map *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool bpf_ma</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
