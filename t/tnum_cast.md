# Function: <code>tnum_cast</code>

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
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a9960)
Location: kernel/bpf/tnum.c:134
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811a9960-ffffffff811a998e: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0e30)
Location: kernel/bpf/tnum.c:144
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811c0e30-ffffffff811c0e5a: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2330)
Location: kernel/bpf/tnum.c:144
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811d2330-ffffffff811d235a: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6a90)
Location: kernel/bpf/tnum.c:145
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811e6a90-ffffffff811e6ab7: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f31f0)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811f31f0-ffffffff811f3217: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215545)
Location: kernel/bpf/tnum.c:150
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81215460-ffffffff81215487: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812171e5)
Location: kernel/bpf/tnum.c:150
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81217100-ffffffff81217127: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a635)
Location: kernel/bpf/tnum.c:150
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8121a550-ffffffff8121a577: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251435)
Location: kernel/bpf/tnum.c:153
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81cb9171-ffffffff81cb91a9: tnum_cast.cold (STB_LOCAL)
ffffffff81251330-ffffffff81251378: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298f15)
Location: kernel/bpf/tnum.c:153
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81e6a43a-ffffffff81e6a472: tnum_cast.cold (STB_LOCAL)
ffffffff81298de0-ffffffff81298e32: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4c25)
Location: kernel/bpf/tnum.c:153
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff82061507-ffffffff8206153f: tnum_cast.cold (STB_LOCAL)
ffffffff812f4ab0-ffffffff812f4b02: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff813220b5)
Location: kernel/bpf/tnum.c:153
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff820e0a94-ffffffff820e0acc: tnum_cast.cold (STB_LOCAL)
ffffffff81321f40-ffffffff81321f92: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81344a35)
Location: kernel/bpf/tnum.c:153
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_with_subreg
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff821bd1a6-ffffffff821bd1de: tnum_cast.cold (STB_LOCAL)
ffffffff81344850-ffffffff813448a2: tnum_cast (STB_GLOBAL)
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
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276f78)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffff800010276f78-ffff800010276fc0: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a97a0)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
c04a97a0-c04a9810: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f350)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
c00000000031f350-c00000000031f370: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001af284)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffe0001af284-ffffffe0001af2c6: tnum_cast (STB_GLOBAL)
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
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb810)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811eb810-ffffffff811eb837: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de5a0)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811de5a0-ffffffff811de5c7: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e95e0)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811e95e0-ffffffff811e9607: tnum_cast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_cast(struct tnum a, u8 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f79b0)
Location: kernel/bpf/tnum.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:coerce_reg_to_size
```
**Symbols:**

```
ffffffff811f79b0-ffffffff811f79d7: tnum_cast (STB_GLOBAL)
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
