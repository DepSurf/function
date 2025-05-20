# Function: <code>__bpf_selem_unlink_storage</code>

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
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fad0)
Location: kernel/bpf/bpf_local_storage.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
**Symbols:**

```
ffffffff8122fad0-ffffffff8122fb52: __bpf_selem_unlink_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225070)
Location: kernel/bpf/bpf_local_storage.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
**Symbols:**

```
ffffffff81225070-ffffffff81225101: __bpf_selem_unlink_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125cff0)
Location: kernel/bpf/bpf_local_storage.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
**Symbols:**

```
ffffffff8125cff0-ffffffff8125d081: __bpf_selem_unlink_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem *selem, bool use_trace_rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a70d0)
Location: kernel/bpf/bpf_local_storage.c:161
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
**Symbols:**

```
ffffffff812a70d0-ffffffff812a71b5: __bpf_selem_unlink_storage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem *selem, bool use_trace_rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81305590)
Location: kernel/bpf/bpf_local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
**Symbols:**

```
ffffffff81305590-ffffffff81305675: __bpf_selem_unlink_storage (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
