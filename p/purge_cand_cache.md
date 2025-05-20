# Function: <code>purge_cand_cache</code>

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
void purge_cand_cache(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ab0f0)
Location: kernel/bpf/btf.c:7586
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff812ab0f0-ffffffff812ab1d4: purge_cand_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void purge_cand_cache(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130aa40)
Location: kernel/bpf/btf.c:8007
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff8130aa40-ffffffff8130ab24: purge_cand_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void purge_cand_cache(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133a580)
Location: kernel/bpf/btf.c:8268
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff8133a580-ffffffff8133a694: purge_cand_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void purge_cand_cache(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813606b0)
Location: kernel/bpf/btf.c:8333
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_module_notify
```
**Symbols:**

```
ffffffff813606b0-ffffffff813607c4: purge_cand_cache (STB_LOCAL)
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
