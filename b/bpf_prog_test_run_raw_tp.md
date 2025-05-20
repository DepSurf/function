# Function: <code>bpf_prog_test_run_raw_tp</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_prog_test_run_raw_tp(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a88290)
Location: net/bpf/test_run.c:259
Inline: False
```
**Symbols:**

```
ffffffff81a88290-ffffffff81a88447: bpf_prog_test_run_raw_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_test_run_raw_tp(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a714e0)
Location: net/bpf/test_run.c:333
Inline: False
```
**Symbols:**

```
ffffffff81a714e0-ffffffff81a716a1: bpf_prog_test_run_raw_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_test_run_raw_tp(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81b2ac00)
Location: net/bpf/test_run.c:334
Inline: False
```
**Symbols:**

```
ffffffff81b2ac00-ffffffff81b2adc1: bpf_prog_test_run_raw_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_test_run_raw_tp(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81cb4dd0)
Location: net/bpf/test_run.c:825
Inline: False
```
**Symbols:**

```
ffffffff81cb4dd0-ffffffff81cb4fb2: bpf_prog_test_run_raw_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_test_run_raw_tp(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81e73320)
Location: net/bpf/test_run.c:857
Inline: False
```
**Symbols:**

```
ffffffff81e73320-ffffffff81e73502: bpf_prog_test_run_raw_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_test_run_raw_tp(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81ecf0b0)
Location: net/bpf/test_run.c:698
Inline: False
```
**Symbols:**

```
ffffffff81ecf0b0-ffffffff81ecf292: bpf_prog_test_run_raw_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_test_run_raw_tp(struct bpf_prog *prog, const union bpf_attr *kattr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81f92a00)
Location: net/bpf/test_run.c:726
Inline: False
```
**Symbols:**

```
ffffffff81f92a00-ffffffff81f92be2: bpf_prog_test_run_raw_tp (STB_GLOBAL)
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
