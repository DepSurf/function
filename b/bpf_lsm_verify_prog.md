# Function: <code>bpf_lsm_verify_prog</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/bpf_lsm.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_verify_prog(struct bpf_verifier_log *vlog, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239680)
Location: kernel/bpf/bpf_lsm.c:38
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81239680-ffffffff812396ed: bpf_lsm_verify_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_verify_prog(struct bpf_verifier_log *vlog, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123de70)
Location: kernel/bpf/bpf_lsm.c:38
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff8123de70-ffffffff8123dedd: bpf_lsm_verify_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_verify_prog(struct bpf_verifier_log *vlog, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278930)
Location: kernel/bpf/bpf_lsm.c:38
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81278930-ffffffff8127899d: bpf_lsm_verify_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_verify_prog(struct bpf_verifier_log *vlog, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c9390)
Location: kernel/bpf/bpf_lsm.c:38
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff812c9390-ffffffff812c9404: bpf_lsm_verify_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_verify_prog(struct bpf_verifier_log *vlog, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813300b0)
Location: kernel/bpf/bpf_lsm.c:97
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff813300b0-ffffffff8133016c: bpf_lsm_verify_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_verify_prog(struct bpf_verifier_log *vlog, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81360d50)
Location: kernel/bpf/bpf_lsm.c:97
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81360d50-ffffffff81360e0c: bpf_lsm_verify_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_verify_prog(struct bpf_verifier_log *vlog, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389c00)
Location: kernel/bpf/bpf_lsm.c:97
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81389c00-ffffffff81389cbc: bpf_lsm_verify_prog (STB_GLOBAL)
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
