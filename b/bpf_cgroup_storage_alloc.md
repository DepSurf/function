# Function: <code>bpf_cgroup_storage_alloc</code>

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
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d85e0)
Location: kernel/bpf/local_storage.c:457
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff811d85e0-ffffffff811d86e8: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ed090)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff811ed090-ffffffff811ed1b4: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f97e0)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff811f97e0-ffffffff811f9904: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d660)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff8121d660-ffffffff8121d782: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812204b0)
Location: kernel/bpf/local_storage.c:486
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff812204b0-ffffffff8122059f: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223f40)
Location: kernel/bpf/local_storage.c:487
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81223f40-ffffffff8122402f: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125be40)
Location: kernel/bpf/local_storage.c:493
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff8125be40-ffffffff8125bf6e: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a5970)
Location: kernel/bpf/local_storage.c:493
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff812a5970-ffffffff812a5b0b: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81303900)
Location: kernel/bpf/local_storage.c:492
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81303900-ffffffff81303b62: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81332330)
Location: kernel/bpf/local_storage.c:499
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81332330-ffffffff81332510: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff813568e0)
Location: kernel/bpf/local_storage.c:499
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff813568e0-ffffffff81356ad4: bpf_cgroup_storage_alloc (STB_GLOBAL)
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
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027f198)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffff80001027f198-ffff80001027f2dc: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b05a8)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
c04b05a8-c04b06d8: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c0000000003292c0)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
c0000000003292c0-c000000000329494: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b5eea)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffe0001b5eea-ffffffe0001b5fda: bpf_cgroup_storage_alloc (STB_GLOBAL)
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
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1e00)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff811f1e00-ffffffff811f1f24: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4b50)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff811e4b50-ffffffff811e4c74: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811efbd0)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff811efbd0-ffffffff811efcf4: bpf_cgroup_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_cgroup_storage *bpf_cgroup_storage_alloc(struct bpf_prog *prog, enum bpf_cgroup_storage_type stype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fe0e0)
Location: kernel/bpf/local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff811fe0e0-ffffffff811fe204: bpf_cgroup_storage_alloc (STB_GLOBAL)
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
