# Function: <code>bpf_list_head_free</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_list_head_free(const struct btf_field *field, void *list_head, struct bpf_spin_lock *spin_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f3d00)
Location: kernel/bpf/helpers.c:1723
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
```
**Symbols:**

```
ffffffff812f3d00-ffffffff812f3db5: bpf_list_head_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_list_head_free(const struct btf_field *field, void *list_head, struct bpf_spin_lock *spin_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81320d70)
Location: kernel/bpf/helpers.c:1810
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
```
**Symbols:**

```
ffffffff81320d70-ffffffff81320e1c: bpf_list_head_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_list_head_free(const struct btf_field *field, void *list_head, struct bpf_spin_lock *spin_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff813432e0)
Location: kernel/bpf/helpers.c:1827
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
```
**Symbols:**

```
ffffffff813432e0-ffffffff8134338e: bpf_list_head_free (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
