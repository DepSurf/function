# Function: <code>bpf_selem_unlink_storage_nolock</code>

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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem, bool uncharge_mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122f990)
Location: kernel/bpf/bpf_local_storage.c:88
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff8122f990-ffffffff8122fad0: bpf_selem_unlink_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem, bool uncharge_mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81224f30)
Location: kernel/bpf/bpf_local_storage.c:88
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff81224f30-ffffffff81225070: bpf_selem_unlink_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem, bool uncharge_mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125ce70)
Location: kernel/bpf/bpf_local_storage.c:88
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff8125ce70-ffffffff8125cff0: bpf_selem_unlink_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem, bool uncharge_mem, bool use_trace_rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a6f10)
Location: kernel/bpf/bpf_local_storage.c:107
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff812a6f10-ffffffff812a70cc: bpf_selem_unlink_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem, bool uncharge_mem, bool use_trace_rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff813053c0)
Location: kernel/bpf/bpf_local_storage.c:116
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_unlink_nolock
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
```
**Symbols:**

```
ffffffff813053c0-ffffffff8130557c: bpf_selem_unlink_storage_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem, bool uncharge_mem, bool reuse_now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81334320)
Location: kernel/bpf/bpf_local_storage.c:253
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage
```
**Symbols:**

```
ffffffff81334320-ffffffff813344cb: bpf_selem_unlink_storage_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81358a10)
Location: kernel/bpf/bpf_local_storage.c:253
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage
```
**Symbols:**

```
ffffffff81358a10-ffffffff81358be3: bpf_selem_unlink_storage_nolock.constprop.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool use_trace_rcu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reuse_now</code>
</li>
<li>
<b>Param removed. </b>
<code>bool use_trace_rcu</code>
</li>
</ul>
</details>
</li>
</ul>
