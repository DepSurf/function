# Function: <code>bpf_convert_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_insn *new_prog, int *new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81730f60)
Location: net/core/filter.c:358
Inline: False
```
**Symbols:**

```
ffffffff81730f60-ffffffff8173191d: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_insn *new_prog, int *new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179bb40)
Location: net/core/filter.c:359
Inline: False
```
**Symbols:**

```
ffffffff8179bb40-ffffffff8179c485: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_insn *new_prog, int *new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817c97d0)
Location: net/core/filter.c:361
Inline: False
```
**Symbols:**

```
ffffffff817c97d0-ffffffff817ca115: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e8700)
Location: net/core/filter.c:370
Inline: False
```
**Symbols:**

```
ffffffff817e8700-ffffffff817e9067: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81863a90)
Location: net/core/filter.c:372
Inline: False
```
**Symbols:**

```
ffffffff81863a90-ffffffff8186445b: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:534
Inline: False
```
**Symbols:**

```
ffffffff818b6e10-ffffffff818b7b7d: bpf_convert_filter (STB_LOCAL)
ffffffff818b87b9-ffffffff818b87c5: bpf_convert_filter.cold.96 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffff818dd3c0-ffffffff818de3fa: bpf_convert_filter (STB_LOCAL)
ffffffff818df411-ffffffff818df41d: bpf_convert_filter.cold.103 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffff8192b8d0-ffffffff8192c3ef: bpf_convert_filter (STB_LOCAL)
ffffffff8192da56-ffffffff8192da62: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffff8195dc10-ffffffff8195e6ef: bpf_convert_filter (STB_LOCAL)
ffffffff8195fcdb-ffffffff8195fce7: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:525
Inline: False
Direct callers:
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:bpf_migrate_filter
```
**Symbols:**

```
ffffffff81a28ab0-ffffffff81a29592: bpf_convert_filter (STB_LOCAL)
ffffffff81a331fd-ffffffff81a33209: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:555
Inline: False
Direct callers:
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:bpf_migrate_filter
```
**Symbols:**

```
ffffffff81a293d0-ffffffff81a29eb2: bpf_convert_filter (STB_LOCAL)
ffffffff81c31749-ffffffff81c31755: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:555
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81a106c0-ffffffff81a1112d: bpf_convert_filter (STB_LOCAL)
ffffffff81c23a52-ffffffff81c23a5e: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:556
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81ac4420-ffffffff81ac4ea0: bpf_convert_filter (STB_LOCAL)
ffffffff81d36fc7-ffffffff81d37034: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:557
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81c3f950-ffffffff81c40438: bpf_convert_filter (STB_LOCAL)
ffffffff81f0390b-ffffffff81f03978: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:559
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81df45e0-ffffffff81df50d5: bpf_convert_filter (STB_LOCAL)
ffffffff820abffe-ffffffff820ac05d: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:559
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81e66020-ffffffff81e66acb: bpf_convert_filter (STB_LOCAL)
ffffffff8212d74d-ffffffff8212d7ae: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:564
Inline: False
Direct callers:
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
```
**Symbols:**

```
ffffffff81f251d0-ffffffff81f25c7b: bpf_convert_filter (STB_LOCAL)
ffffffff8220f49a-ffffffff8220f4fb: bpf_convert_filter.cold (STB_LOCAL)
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
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfe9d8)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffff800010bfe9d8-ffff800010bff19c: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1a0a0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
c0d1a0a0-c0d1abcc: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce9980)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
c000000000ce9980-c000000000cea6a0: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007809cc)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffe0007809cc-ffffffe0007810a4: bpf_convert_filter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffff818fdbe0-ffffffff818fe6bf: bpf_convert_filter (STB_LOCAL)
ffffffff818ffcab-ffffffff818ffcb7: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffff818b7a10-ffffffff818b84ef: bpf_convert_filter (STB_LOCAL)
ffffffff818b9adb-ffffffff818b9ae7: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffff8194ec10-ffffffff8194f6ef: bpf_convert_filter (STB_LOCAL)
ffffffff81950cdb-ffffffff81950ce7: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int bpf_convert_filter(struct sock_filter *prog, int len, struct bpf_prog *new_prog, int *new_len, bool *seen_ld_abs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:536
Inline: False
```
**Symbols:**

```
ffffffff819705e0-ffffffff819710bf: bpf_convert_filter (STB_LOCAL)
ffffffff819726ab-ffffffff819726b7: bpf_convert_filter.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_insn *new_prog</code> ➡️ <code>struct bpf_prog *new_prog</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *seen_ld_abs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
