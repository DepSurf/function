# Function: <code>btf_id_set_contains</code>

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
bool btf_id_set_contains(const struct btf_id_set *set, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122cd20)
Location: kernel/bpf/btf.c:5753
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
```
**Symbols:**

```
ffffffff8122cd20-ffffffff8122cd53: btf_id_set_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool btf_id_set_contains(const struct btf_id_set *set, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81231b00)
Location: kernel/bpf/btf.c:5951
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - net/bpf/test_run.c:bpf_prog_test_check_kfunc_call
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_kfunc_call
```
**Symbols:**

```
ffffffff81231b00-ffffffff81231b33: btf_id_set_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool btf_id_set_contains(const struct btf_id_set *set, u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126aac0)
Location: kernel/bpf/btf.c:6004
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - net/bpf/test_run.c:bpf_prog_test_check_kfunc_call
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_kfunc_call
```
**Symbols:**

```
ffffffff8126aac0-ffffffff8126aaf3: btf_id_set_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool btf_id_set_contains(const struct btf_id_set *set, u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b800c)
Location: kernel/bpf/btf.c:6737
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
```
**Symbols:**

```
ffffffff812b7940-ffffffff812b7982: btf_id_set_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a6ac6)
Location: include/linux/btf.h:460
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff812ef1ce)
Location: include/linux/btf.h:460
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff8131a570)
Location: include/linux/btf.h:460
Inline: True
```
```
In kernel/bpf/bpf_lsm.c (ffffffff81330241)
Location: include/linux/btf.h:460
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c8b86)
Location: include/linux/btf.h:476
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8131bb8d)
Location: include/linux/btf.h:476
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81349c02)
Location: include/linux/btf.h:476
Inline: True
```
```
In kernel/bpf/bpf_lsm.c (ffffffff81360ee1)
Location: include/linux/btf.h:476
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e5bf6)
Location: include/linux/btf.h:487
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8133df36)
Location: include/linux/btf.h:487
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81370352)
Location: include/linux/btf.h:487
Inline: True
```
```
In kernel/bpf/bpf_lsm.c (ffffffff81389d91)
Location: include/linux/btf.h:487
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
  - kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
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
</ul>
