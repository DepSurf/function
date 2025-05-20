# Function: <code>tnum_is_aligned</code>

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
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a9990)
Location: kernel/bpf/tnum.c:141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811a9990-ffffffff811a99b6: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0e60)
Location: kernel/bpf/tnum.c:151
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811c0e60-ffffffff811c0e82: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2360)
Location: kernel/bpf/tnum.c:151
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d2360-ffffffff811d2382: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6ac0)
Location: kernel/bpf/tnum.c:152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811e6ac0-ffffffff811e6ae2: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f3220)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811f3220-ffffffff811f3242: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215490)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81215490-ffffffff812154b2: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81217130)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81217130-ffffffff81217152: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a580)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff8121a580-ffffffff8121a5a2: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251380)
Location: kernel/bpf/tnum.c:160
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81251380-ffffffff812513a2: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298e40)
Location: kernel/bpf/tnum.c:160
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81298e40-ffffffff81298e6c: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4b20)
Location: kernel/bpf/tnum.c:160
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff812f4b20-ffffffff812f4b4c: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81321fb0)
Location: kernel/bpf/tnum.c:160
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81321fb0-ffffffff81321fdc: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff813448c0)
Location: kernel/bpf/tnum.c:160
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff813448c0-ffffffff813448ec: tnum_is_aligned (STB_GLOBAL)
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
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276fc0)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffff800010276fc0-ffff80001027700c: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a9810)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
c04a9810-c04a987c: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f370)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
c00000000031f370-c00000000031f3a8: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001af2c6)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffe0001af2c6-ffffffe0001af304: tnum_is_aligned (STB_GLOBAL)
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
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb840)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811eb840-ffffffff811eb862: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de5d0)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811de5d0-ffffffff811de5f2: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e9610)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811e9610-ffffffff811e9632: tnum_is_aligned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tnum_is_aligned(struct tnum a, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f79e0)
Location: kernel/bpf/tnum.c:157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811f79e0-ffffffff811f7a02: tnum_is_aligned (STB_GLOBAL)
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
