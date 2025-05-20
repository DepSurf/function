# Function: <code>bpf_prog_test_run_sk_lookup</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a720b0)
Location: net/bpf/test_run.c:822
Inline: False
```
**Symbols:**

```
ffffffff81a720b0-ffffffff81a72516: bpf_prog_test_run_sk_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/bpf/test_run.c (0)
Location: net/bpf/test_run.c:920
Inline: False
```
**Symbols:**

```
ffffffff81d395aa-ffffffff81d395e2: bpf_prog_test_run_sk_lookup.cold (STB_LOCAL)
ffffffff81b2b9f0-ffffffff81b2be83: bpf_prog_test_run_sk_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/bpf/test_run.c (0)
Location: net/bpf/test_run.c:1482
Inline: False
```
**Symbols:**

```
ffffffff81f05d01-ffffffff81f05d47: bpf_prog_test_run_sk_lookup.cold (STB_LOCAL)
ffffffff81cb5ef0-ffffffff81cb64aa: bpf_prog_test_run_sk_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/bpf/test_run.c (0)
Location: net/bpf/test_run.c:1508
Inline: False
```
**Symbols:**

```
ffffffff820ada1c-ffffffff820ada62: bpf_prog_test_run_sk_lookup.cold (STB_LOCAL)
ffffffff81e743d0-ffffffff81e7497f: bpf_prog_test_run_sk_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/bpf/test_run.c (0)
Location: net/bpf/test_run.c:1351
Inline: False
```
**Symbols:**

```
ffffffff8212ec4f-ffffffff8212ec94: bpf_prog_test_run_sk_lookup.cold (STB_LOCAL)
ffffffff81ed0180-ffffffff81ed074c: bpf_prog_test_run_sk_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_prog_test_run_sk_lookup(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/bpf/test_run.c (0)
Location: net/bpf/test_run.c:1379
Inline: False
```
**Symbols:**

```
ffffffff822109c8-ffffffff82210a0d: bpf_prog_test_run_sk_lookup.cold (STB_LOCAL)
ffffffff81f93ae0-ffffffff81f940ac: bpf_prog_test_run_sk_lookup (STB_GLOBAL)
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
