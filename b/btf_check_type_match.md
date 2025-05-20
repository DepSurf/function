# Function: <code>btf_check_type_match</code>

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
int btf_check_type_match(struct bpf_verifier_env *env, struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812255d0)
Location: kernel/bpf/btf.c:4344
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff812255d0-ffffffff8122564d: btf_check_type_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log *log, const struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122be10)
Location: kernel/bpf/btf.c:5268
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff8122be10-ffffffff8122be96: btf_check_type_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log *log, const struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81230e70)
Location: kernel/bpf/btf.c:5353
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81230e70-ffffffff81230ef6: btf_check_type_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log *log, const struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81269d80)
Location: kernel/bpf/btf.c:5406
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81269d80-ffffffff81269e06: btf_check_type_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log *log, const struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b6b80)
Location: kernel/bpf/btf.c:5960
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff812b6b80-ffffffff812b6c4d: btf_check_type_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log *log, const struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81317eb0)
Location: kernel/bpf/btf.c:6633
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81317eb0-ffffffff81317f7d: btf_check_type_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log *log, const struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81347e40)
Location: kernel/bpf/btf.c:6735
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81347e40-ffffffff81347f10: btf_check_type_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log *log, const struct bpf_prog *prog, struct btf *btf2, const struct btf_type *t2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136e2b0)
Location: kernel/bpf/btf.c:6907
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff8136e2b0-ffffffff8136e380: btf_check_type_match (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_log *log</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_env *env</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct bpf_prog *prog</code> ➡️ <code>const struct bpf_prog *prog</code>
</li>
</ul>
</details>
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
