# Function: <code>btf_get</code>

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
void btf_get(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229260)
Location: kernel/bpf/btf.c:1527
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81229260-ffffffff812292a2: btf_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_get(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122db00)
Location: kernel/bpf/btf.c:1528
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff8122db00-ffffffff8122db42: btf_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void btf_get(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812666e2)
Location: kernel/bpf/btf.c:1528
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
**Symbols:**

```
ffffffff81266530-ffffffff81266572: btf_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void btf_get(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b3555)
Location: kernel/bpf/btf.c:1656
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_copy_kptr_off_tab
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
```
**Symbols:**

```
ffffffff812b30b0-ffffffff812b311c: btf_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void btf_get(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813139f5)
Location: kernel/bpf/btf.c:1679
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff813134d0-ffffffff8131353c: btf_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void btf_get(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348ffa)
Location: kernel/bpf/btf.c:1709
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff813431a0-ffffffff8134320c: btf_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void btf_get(struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136f72a)
Location: kernel/bpf/btf.c:1710
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff813690d0-ffffffff8136913c: btf_get (STB_GLOBAL)
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
