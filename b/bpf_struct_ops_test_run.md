# Function: <code>bpf_struct_ops_test_run</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_struct_ops_test_run(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81cb6850)
Location: net/bpf/bpf_dummy_struct_ops.c:77
Inline: False
```
**Symbols:**

```
ffffffff81cb6850-ffffffff81cb6b80: bpf_struct_ops_test_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_struct_ops_test_run(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81e74dc0)
Location: net/bpf/bpf_dummy_struct_ops.c:77
Inline: False
```
**Symbols:**

```
ffffffff81e74dc0-ffffffff81e750e0: bpf_struct_ops_test_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_struct_ops_test_run(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed0fb0)
Location: net/bpf/bpf_dummy_struct_ops.c:77
Inline: False
```
**Symbols:**

```
ffffffff81ed0fb0-ffffffff81ed12c0: bpf_struct_ops_test_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_struct_ops_test_run(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f949d0)
Location: net/bpf/bpf_dummy_struct_ops.c:82
Inline: False
```
**Symbols:**

```
ffffffff81f949d0-ffffffff81f94d83: bpf_struct_ops_test_run (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
