# Function: <code>bpf_prog_test_run_syscall</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_test_run_syscall(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81b2be90)
Location: net/bpf/test_run.c:1023
Inline: False
```
**Symbols:**

```
ffffffff81b2be90-ffffffff81b2c0c0: bpf_prog_test_run_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_test_run_syscall(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81cb64b0)
Location: net/bpf/test_run.c:1585
Inline: False
```
**Symbols:**

```
ffffffff81cb64b0-ffffffff81cb66bc: bpf_prog_test_run_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_test_run_syscall(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81e74990)
Location: net/bpf/test_run.c:1608
Inline: False
```
**Symbols:**

```
ffffffff81e74990-ffffffff81e74ba5: bpf_prog_test_run_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_test_run_syscall(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81ed0760)
Location: net/bpf/test_run.c:1451
Inline: False
```
**Symbols:**

```
ffffffff81ed0760-ffffffff81ed0975: bpf_prog_test_run_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_test_run_syscall(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81f940c0)
Location: net/bpf/test_run.c:1479
Inline: False
```
**Symbols:**

```
ffffffff81f940c0-ffffffff81f942d5: bpf_prog_test_run_syscall (STB_GLOBAL)
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
