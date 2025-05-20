# Function: <code>__bpf_obj_drop_impl</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_obj_drop_impl(void *p, const struct btf_record *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81320cf0)
Location: kernel/bpf/helpers.c:1904
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
  - kernel/bpf/helpers.c:bpf_list_push_back_impl
  - kernel/bpf/helpers.c:bpf_list_push_front_impl
  - kernel/bpf/helpers.c:bpf_obj_drop_impl
  - kernel/bpf/helpers.c:bpf_rb_root_free
  - kernel/bpf/helpers.c:bpf_list_head_free
```
**Symbols:**

```
ffffffff81320cf0-ffffffff81320d5a: __bpf_obj_drop_impl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_obj_drop_impl(void *p, const struct btf_record *rec, bool percpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff813434a6)
Location: kernel/bpf/helpers.c:1927
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_drop_impl
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
  - kernel/bpf/helpers.c:bpf_list_push_back_impl
  - kernel/bpf/helpers.c:bpf_list_push_front_impl
  - kernel/bpf/helpers.c:bpf_rb_root_free
  - kernel/bpf/helpers.c:bpf_list_head_free
```
**Symbols:**

```
ffffffff81343250-ffffffff813432cc: __bpf_obj_drop_impl (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool percpu</code>
</li>
</ul>
</details>
</li>
</ul>
