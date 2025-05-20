# Function: <code>bpf_trampoline_lookup</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_lookup(u64 key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121ee70)
Location: kernel/bpf/trampoline.c:66
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff8121ee70-ffffffff8121f086: bpf_trampoline_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_lookup(u64 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222510)
Location: kernel/bpf/trampoline.c:60
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
**Symbols:**

```
ffffffff81222510-ffffffff81222642: bpf_trampoline_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81226fb2)
Location: kernel/bpf/trampoline.c:61
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125f0b2)
Location: kernel/bpf/trampoline.c:61
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a96f1)
Location: kernel/bpf/trampoline.c:73
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_lookup(u64 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308570)
Location: kernel/bpf/trampoline.c:135
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
```
**Symbols:**

```
ffffffff81308570-ffffffff813086ea: bpf_trampoline_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_lookup(u64 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81337350)
Location: kernel/bpf/trampoline.c:134
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
```
**Symbols:**

```
ffffffff81337350-ffffffff813374ca: bpf_trampoline_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_lookup(u64 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135d1d0)
Location: kernel/bpf/trampoline.c:134
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
```
**Symbols:**

```
ffffffff8135d1d0-ffffffff8135d3a8: bpf_trampoline_lookup (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
