# Function: <code>btf_check_type_tags</code>

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
int btf_check_type_tags(struct btf_verifier_env *env, struct btf *btf, int start_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ac210)
Location: kernel/bpf/btf.c:4809
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff812ac210-ffffffff812ac3d8: btf_check_type_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_check_type_tags(struct btf_verifier_env *env, struct btf *btf, int start_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130bb80)
Location: kernel/bpf/btf.c:5348
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8130bb80-ffffffff8130bd48: btf_check_type_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_check_type_tags(struct btf_verifier_env *env, struct btf *btf, int start_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133abd0)
Location: kernel/bpf/btf.c:5411
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8133abd0-ffffffff8133adaa: btf_check_type_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_check_type_tags(struct btf_verifier_env *env, struct btf *btf, int start_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81360d00)
Location: kernel/bpf/btf.c:5419
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81360d00-ffffffff81360eda: btf_check_type_tags (STB_LOCAL)
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
