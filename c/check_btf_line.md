# Function: <code>check_btf_line</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d08a5)
Location: kernel/bpf/verifier.c:5118
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9ba8)
Location: kernel/bpf/verifier.c:6520
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (ffffffff811e62a8)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81205d50)
Location: kernel/bpf/verifier.c:7668
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81205d50-ffffffff8120602c: check_btf_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81205900)
Location: kernel/bpf/verifier.c:8445
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81205900-ffffffff81205bd8: check_btf_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207700)
Location: kernel/bpf/verifier.c:9623
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81207700-ffffffff812079d3: check_btf_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123aea0)
Location: kernel/bpf/verifier.c:9951
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8123aea0-ffffffff8123b267: check_btf_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812806d0)
Location: kernel/bpf/verifier.c:10932
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812806d0-ffffffff81280af5: check_btf_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d8440)
Location: kernel/bpf/verifier.c:12904
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812d8440-ffffffff812d8857: check_btf_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81301320)
Location: kernel/bpf/verifier.c:14883
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81301320-ffffffff81301736: check_btf_line (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_btf_line(struct bpf_verifier_env *env, const union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81320410)
Location: kernel/bpf/verifier.c:15910
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81320410-ffffffff8132082b: check_btf_line (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff800010269678)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (c049b9a0)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (c00000000030f410)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (ffffffe0001a439c)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (ffffffff811de8c8)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (ffffffff811d1688)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (ffffffff811dc698)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
In kernel/bpf/verifier.c (ffffffff811eaaa8)
Location: kernel/bpf/verifier.c:6535
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>union bpf_attr *uattr</code> ➡️ <code>bpfptr_t uattr</code>
</li>
</ul>
</details>
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
