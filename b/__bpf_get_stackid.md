# Function: <code>__bpf_get_stackid</code>

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
long int __bpf_get_stackid(struct bpf_map *map, struct perf_callchain_entry *trace, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812336a0)
Location: kernel/bpf/stackmap.c:387
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff812336a0-ffffffff81233aeb: __bpf_get_stackid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __bpf_get_stackid(struct bpf_map *map, struct perf_callchain_entry *trace, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81237460)
Location: kernel/bpf/stackmap.c:252
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81237460-ffffffff812378ad: __bpf_get_stackid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __bpf_get_stackid(struct bpf_map *map, struct perf_callchain_entry *trace, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81271a30)
Location: kernel/bpf/stackmap.c:259
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81271a30-ffffffff81271e7d: __bpf_get_stackid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __bpf_get_stackid(struct bpf_map *map, struct perf_callchain_entry *trace, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812c0bb0)
Location: kernel/bpf/stackmap.c:213
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff812c0bb0-ffffffff812c0fbb: __bpf_get_stackid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __bpf_get_stackid(struct bpf_map *map, struct perf_callchain_entry *trace, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81324450)
Location: kernel/bpf/stackmap.c:213
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81324450-ffffffff8132485b: __bpf_get_stackid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __bpf_get_stackid(struct bpf_map *map, struct perf_callchain_entry *trace, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff813546b0)
Location: kernel/bpf/stackmap.c:210
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff813546b0-ffffffff81354aba: __bpf_get_stackid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __bpf_get_stackid(struct bpf_map *map, struct perf_callchain_entry *trace, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8137d020)
Location: kernel/bpf/stackmap.c:210
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff8137d020-ffffffff8137d42a: __bpf_get_stackid (STB_LOCAL)
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
