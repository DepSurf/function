# Function: <code>btf_member_is_reg_int</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811db270)
Location: kernel/bpf/btf.c:552
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff811db270-ffffffff811db359: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f0860)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff811f0860-ffffffff811f094e: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fcf70)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff811fcf70-ffffffff811fd05e: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223240)
Location: kernel/bpf/btf.c:642
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff81223240-ffffffff8122332c: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229780)
Location: kernel/bpf/btf.c:745
Inline: False
```
**Symbols:**

```
ffffffff81229780-ffffffff8122986c: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122e010)
Location: kernel/bpf/btf.c:747
Inline: False
```
**Symbols:**

```
ffffffff8122e010-ffffffff8122e0fc: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81266c10)
Location: kernel/bpf/btf.c:747
Inline: False
```
**Symbols:**

```
ffffffff81266c10-ffffffff81266cfc: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b3e40)
Location: kernel/bpf/btf.c:842
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff812b3e40-ffffffff812b3f3b: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81314350)
Location: kernel/bpf/btf.c:844
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff81314350-ffffffff8131444b: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81344250)
Location: kernel/bpf/btf.c:863
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff81344250-ffffffff81344350: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136a1e0)
Location: kernel/bpf/btf.c:864
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff8136a1e0-ffffffff8136a2e0: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010283cf0)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffff800010283cf0-ffff800010283e08: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b43fc)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
c04b43fc-c04b451c: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032e3b0)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
c00000000032e3b0-c00000000032e51c: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b9610)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffe0001b9610-ffffffe0001b96da: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f5590)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff811f5590-ffffffff811f567e: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e82e0)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff811e82e0-ffffffff811e83ce: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3360)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff811f3360-ffffffff811f344e: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool btf_member_is_reg_int(const struct btf *btf, const struct btf_type *s, const struct btf_member *m, u32 expected_offset, u32 expected_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81201870)
Location: kernel/bpf/btf.c:627
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
  - kernel/bpf/local_storage.c:cgroup_storage_check_btf
```
**Symbols:**

```
ffffffff81201870-ffffffff8120195e: btf_member_is_reg_int (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
