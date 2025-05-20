# Function: <code>bpf_lsm_is_sleepable_hook</code>

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
bool bpf_lsm_is_sleepable_hook(u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812386c5)
Location: kernel/bpf/bpf_lsm.c:218
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff812396f0-ffffffff81239709: bpf_lsm_is_sleepable_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool bpf_lsm_is_sleepable_hook(u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123cea5)
Location: kernel/bpf/bpf_lsm.c:217
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff8123dee0-ffffffff8123def9: bpf_lsm_is_sleepable_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool bpf_lsm_is_sleepable_hook(u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277935)
Location: kernel/bpf/bpf_lsm.c:217
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff812789a0-ffffffff812789b9: bpf_lsm_is_sleepable_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool bpf_lsm_is_sleepable_hook(u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c7645)
Location: kernel/bpf/bpf_lsm.c:256
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff812c9410-ffffffff812c9431: bpf_lsm_is_sleepable_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool bpf_lsm_is_sleepable_hook(u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81330180)
Location: kernel/bpf/bpf_lsm.c:360
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81330180-ffffffff813301ec: bpf_lsm_is_sleepable_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool bpf_lsm_is_sleepable_hook(u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81360e20)
Location: kernel/bpf/bpf_lsm.c:360
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81360e20-ffffffff81360e8c: bpf_lsm_is_sleepable_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool bpf_lsm_is_sleepable_hook(u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389cd0)
Location: kernel/bpf/bpf_lsm.c:372
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81389cd0-ffffffff81389d3c: bpf_lsm_is_sleepable_hook (STB_GLOBAL)
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
