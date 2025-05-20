# Function: <code>bpf_dev_bound_kfunc_check</code>

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
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_dev_bound_kfunc_check(struct bpf_verifier_log *log, struct bpf_prog_aux *prog_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:813
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff820e12e4-ffffffff820e130d: bpf_dev_bound_kfunc_check.cold (STB_LOCAL)
ffffffff81352e00-ffffffff81352e79: bpf_dev_bound_kfunc_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_dev_bound_kfunc_check(struct bpf_verifier_log *log, struct bpf_prog_aux *prog_aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:823
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff821bdb4b-ffffffff821bdb74: bpf_dev_bound_kfunc_check.cold (STB_LOCAL)
ffffffff8137a2e0-ffffffff8137a359: bpf_dev_bound_kfunc_check (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
