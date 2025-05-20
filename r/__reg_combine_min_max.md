# Function: <code>__reg_combine_min_max</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a26e0)
Location: kernel/bpf/verifier.c:2789
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811a26e0-ffffffff811a2927: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6bc0)
Location: kernel/bpf/verifier.c:3580
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811b6bc0-ffffffff811b6e03: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c5ce0)
Location: kernel/bpf/verifier.c:4277
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811c5ce0-ffffffff811c5f23: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6bb0)
Location: kernel/bpf/verifier.c:5552
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811d6bb0-ffffffff811d6df3: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3210)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e3210-ffffffff811e3453: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203f00)
Location: kernel/bpf/verifier.c:6623
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81203f00-ffffffff81204172: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203e90)
Location: kernel/bpf/verifier.c:7275
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81203e90-ffffffff81204102: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204e60)
Location: kernel/bpf/verifier.c:8438
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81204e60-ffffffff812050da: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81237990)
Location: kernel/bpf/verifier.c:8731
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff81237990-ffffffff81237c0a: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127bf30)
Location: kernel/bpf/verifier.c:9726
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff8127bf30-ffffffff8127bfea: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d2530)
Location: kernel/bpf/verifier.c:11649
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff812d2530-ffffffff812d25ea: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813079f0)
Location: kernel/bpf/verifier.c:13580
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff813079f0-ffffffff81307aaa: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff8000102664b8)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffff8000102664b8-ffff8000102666a8: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0498bf8)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c0498bf8-c0498d48: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030b2a0)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c00000000030b2a0-c00000000030b54c: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a18fc)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffe0001a18fc-ffffffe0001a1acc: __reg_combine_min_max (STB_LOCAL)
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
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db830)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811db830-ffffffff811dba73: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ce5f0)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811ce5f0-ffffffff811ce833: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9600)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811d9600-ffffffff811d9843: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __reg_combine_min_max(struct bpf_reg_state *src_reg, struct bpf_reg_state *dst_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7a10)
Location: kernel/bpf/verifier.c:5562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e7a10-ffffffff811e7c53: __reg_combine_min_max (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
