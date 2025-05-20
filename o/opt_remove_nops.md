# Function: <code>opt_remove_nops</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e5235)
Location: kernel/bpf/verifier.c:8382
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f1a94)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int opt_remove_nops(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202e40)
Location: kernel/bpf/verifier.c:9511
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81202e40-ffffffff81202ed8: opt_remove_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int opt_remove_nops(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202b70)
Location: kernel/bpf/verifier.c:10441
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81202b70-ffffffff81202c08: opt_remove_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81217cee)
Location: kernel/bpf/verifier.c:11707
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124e383)
Location: kernel/bpf/verifier.c:12090
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8129525e)
Location: kernel/bpf/verifier.c:13149
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812effd6)
Location: kernel/bpf/verifier.c:15126
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131cb74)
Location: kernel/bpf/verifier.c:17343
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8133ed70)
Location: kernel/bpf/verifier.c:18497
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010275190)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a77d8)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000031d02c)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001ad986)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ea0b4)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dce74)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7e84)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f6234)
Location: kernel/bpf/verifier.c:8397
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
