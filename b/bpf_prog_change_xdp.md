# Function: <code>bpf_prog_change_xdp</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a331e0)
Location: net/core/filter.c:9244
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_uninstall
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81a331e0-ffffffff81a331fd: bpf_prog_change_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a355a0)
Location: net/core/filter.c:10295
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_install
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81a355a0-ffffffff81a355bd: bpf_prog_change_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1c6f0)
Location: net/core/filter.c:10437
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_install
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81a1c6f0-ffffffff81a1c70d: bpf_prog_change_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acfeb0)
Location: net/core/filter.c:10636
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_install
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81acfeb0-ffffffff81acfecd: bpf_prog_change_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4d670)
Location: net/core/filter.c:11168
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_install
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81c4d670-ffffffff81c4d697: bpf_prog_change_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e02590)
Location: net/core/filter.c:11374
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_install
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81e02590-ffffffff81e025b7: bpf_prog_change_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e74940)
Location: net/core/filter.c:11523
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_install
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81e74940-ffffffff81e74967: bpf_prog_change_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_change_xdp(struct bpf_prog *prev_prog, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f34100)
Location: net/core/filter.c:11614
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_install
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
**Symbols:**

```
ffffffff81f34100-ffffffff81f34127: bpf_prog_change_xdp (STB_GLOBAL)
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
