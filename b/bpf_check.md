# Function: <code>bpf_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81176300)
Location: kernel/bpf/verifier.c:2183
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81176300-ffffffff81176c44: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81184d20)
Location: kernel/bpf/verifier.c:2678
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81184d20-ffffffff8118571c: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81192260)
Location: kernel/bpf/verifier.c:3144
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81192260-ffffffff8119297d: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81199050)
Location: kernel/bpf/verifier.c:3744
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81199050-ffffffff811997d2: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a7f90)
Location: kernel/bpf/verifier.c:4645
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811a7f90-ffffffff811a8a7f: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811be9f0)
Location: kernel/bpf/verifier.c:5863
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811be9f0-ffffffff811bfe38: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cf610)
Location: kernel/bpf/verifier.c:7149
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811cf610-ffffffff811d1288: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4110)
Location: kernel/bpf/verifier.c:9209
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811e4110-ffffffff811e5450: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f0960)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811f0960-ffffffff811f1caf: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212fc0)
Location: kernel/bpf/verifier.c:10883
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81212fc0-ffffffff812138e4: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812147a0)
Location: kernel/bpf/verifier.c:11958
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff812147a0-ffffffff812151ba: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81216ff0)
Location: kernel/bpf/verifier.c:13283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81216ff0-ffffffff81217ec3: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13727
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81cb8f6d-ffffffff81cb8fe3: bpf_check.cold (STB_LOCAL)
ffffffff8124d7a0-ffffffff8124e558: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:14891
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81e6a22a-ffffffff81e6a29c: bpf_check.cold (STB_LOCAL)
ffffffff81294710-ffffffff81295590: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, bpfptr_t uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:17062
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff82061331-ffffffff8206139e: bpf_check.cold (STB_LOCAL)
ffffffff812ef2c0-ffffffff812f02c6: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, bpfptr_t uattr, __u32 uattr_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:19393
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff820e07ba-ffffffff820e0844: bpf_check.cold (STB_LOCAL)
ffffffff8131bc90-ffffffff8131ceb9: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, bpfptr_t uattr, __u32 uattr_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:20740
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff821bceeb-ffffffff821bcf3d: bpf_check.cold (STB_LOCAL)
ffffffff8133e030-ffffffff8133f0f2: bpf_check (STB_GLOBAL)
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
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010274120)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffff800010274120-ffff800010275274: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a6794)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
c04a6794-c04a7aa0: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000031bd10)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
c00000000031bd10-c00000000031d264: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001aca9e)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffe0001aca9e-ffffffe0001ada1a: bpf_check (STB_GLOBAL)
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
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e8f80)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811e8f80-ffffffff811ea2cf: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dbd40)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811dbd40-ffffffff811dd08f: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6d50)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811e6d50-ffffffff811e809f: bpf_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_check(struct bpf_prog **prog, union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f5100)
Location: kernel/bpf/verifier.c:9224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811f5100-ffffffff811f644f: bpf_check (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>union bpf_attr *uattr</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u32 uattr_size</code>
</li>
</ul>
</details>
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
