# Function: <code>cgroup_get_from_id</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup *cgroup_get_from_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811925c0)
Location: kernel/cgroup/cgroup.c:5968
Inline: False
```
**Symbols:**

```
ffffffff811925c0-ffffffff8119267c: cgroup_get_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup *cgroup_get_from_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c3260)
Location: kernel/cgroup/cgroup.c:5979
Inline: False
Direct callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
**Symbols:**

```
ffffffff811c3260-ffffffff811c3311: cgroup_get_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup *cgroup_get_from_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81208100)
Location: kernel/cgroup/cgroup.c:6191
Inline: False
Direct callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
**Symbols:**

```
ffffffff81208100-ffffffff81208290: cgroup_get_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup *cgroup_get_from_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121d890)
Location: kernel/cgroup/cgroup.c:6172
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_cgroup_from_id
  - kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
**Symbols:**

```
ffffffff8121d890-ffffffff8121da2a: cgroup_get_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup *cgroup_get_from_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812354c0)
Location: kernel/cgroup/cgroup.c:6205
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_cgroup_from_id
  - kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
**Symbols:**

```
ffffffff812354c0-ffffffff8123564b: cgroup_get_from_id (STB_GLOBAL)
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
